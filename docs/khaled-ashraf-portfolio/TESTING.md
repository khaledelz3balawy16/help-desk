# Testing and validation

## Preparation checks completed

- Captured source at the recorded commit.
- Checked archive paths, symlinks, and file inclusion rules.
- Replaced detected credential literals, connection strings, and contact addresses with placeholders.
- Removed data exports, runtime environments, private keys, generated output, and internal assistant artifacts.
- Re-scanned the prepared text for the supported sensitive-value patterns.
- Parsed generated JSON documents and package manifests.

## Application validation

Dependencies were not installed. Application tests, servers, migrations, seeders, and database or external-service requests were not run. Runtime correctness after configuration and data removal remains to be verified by the project maintainer.

## Existing test sources

- `backend/knowledge_base/tests.py`
- `backend/support_portal/test_closure_email.py`
- `backend/support_portal/test_lms_knowledge.py`
- `backend/support_portal/test_merge_integration.py`
- `backend/support_portal/test_notification_dismissals_and_retention.py`
- `backend/support_portal/test_submitted_for_learner_notifications.py`
- `backend/support_portal/test_support_hardening.py`
- `backend/support_portal/test_ticket_detail_consistency.py`
- `backend/support_portal/test_ticket_ownership.py`
- `backend/support_portal/tests.py`
- `frontend/src/components/ui/aspect-ratio.tsx`
- `frontend/src/test/admin-login.test.tsx`
- `frontend/src/test/admin-session.test.ts`
- `frontend/src/test/agent-dashboard.runtime.test.tsx`
- `frontend/src/test/chat-support-message-bubble.test.tsx`
- `frontend/src/test/close-ticket-dialog.test.tsx`
- `frontend/src/test/email-verification.test.tsx`
- `frontend/src/test/example.test.ts`
- `frontend/src/test/inquiry-details.test.tsx`
- `frontend/src/test/my-tickets.test.tsx`
- `frontend/src/test/require-admin.test.tsx`
- `frontend/src/test/support-layout-admin-return.test.tsx`
- `frontend/src/test/support-options.test.tsx`
- `frontend/src/test/ticket-status-editor.test.tsx`
- `frontend/src/test/ticket-status-navigation.test.tsx`
- `frontend/src/test/ticket-status.test.tsx`
- `frontend/vitest.config.ts`
