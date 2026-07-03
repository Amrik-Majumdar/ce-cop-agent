# Security Policy

Last updated: July 2026

CE Cop Agent is a real estate lead-response workflow project. Security concerns should be reported privately, especially if they involve credentials, private lead records, contact details, routing rules, user data, or production configuration.

## Reporting A Security Issue

Please report security concerns privately by email:

**majumdar.amrik@gmail.com**

Include:

- a summary of the issue
- affected URL or file, if applicable
- steps to reproduce
- screenshots or logs if they do not expose private data

## Public-Safe Rules

- Do not commit real customer, lead, or inbox records.
- Do not commit API keys, tokens, or `.env` files.
- Keep payment details and production configuration out of the repository.
- Use `.env.example` only for placeholder values.
- Review any future backend before handling real lead records.
