# Qala JS

### Minimal Node.js solution for secure access to sensitive encrypted data, using ephemeral tokens.


* Encrypts sensitive data: Stores complex objects (tokens, keys, etc.) in an encrypted form using AES-256-CBC.
* Initial credential-based access: Uses a one-time credential (id/secret + IP check) to decrypt data and generate a short-lived token.
* Token-based sessions: Allows subsequent access and token refresh via token-based requests, automatically extending the session.
* Credential clearance: Erases long-lived credentials post-initialization, reducing risk even if the server is later compromised.


Ideal as a simple, low-effort, yet high standart security mechanism for community exploration or further development.
