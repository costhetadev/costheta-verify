# costheta-verify

Public verifier for costheta decision certificates.

Verifies: the canonical hash of the certificate body, the Ed25519
signature (RFC 8032) and the ML-DSA signature (FIPS 204), against the
public keys published at costheta.dev/keys.

Code lands here shortly. The certificate format (v0.3) is specified in the federation proposal: https://github.com/costhetadev/federation-proposal
