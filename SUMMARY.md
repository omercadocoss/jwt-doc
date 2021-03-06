# Table of contents

* [Introduction](README.md)
* [Components](components/README.md)
  * [Algorithm Management \(JWA\)](components/algorithm-management-jwa.md)
  * [Key \(JWK\) and Key Set \(JWKSet\)](components/key-jwk-and-key-set-jwkset/README.md)
    * [Key Management \(JWK\)](components/key-jwk-and-key-set-jwkset/key-management.md)
    * [Key Set Management \(JWKSet\)](components/key-jwk-and-key-set-jwkset/key-set-management.md)
  * [Header Checker](components/header-checker.md)
  * [Claim Checker](components/claim-checker.md)
  * [Signed Tokens \(JWS\)](components/signed-tokens-jws/README.md)
    * [Signature Algorithms](components/signed-tokens-jws/signature-algorithms.md)
    * [JWS Creation](components/signed-tokens-jws/jws-creation.md)
    * [JWS Loading](components/signed-tokens-jws/jws-loading.md)
  * [Encrypted Tokens \(JWE\)](components/encrypted-tokens-jwe/README.md)
    * [Encryption Algorithms](components/encrypted-tokens-jwe/encryption-algorithms.md)
    * [JWE Creation](components/encrypted-tokens-jwe/jwe-creation.md)
    * [JWE Loading](components/encrypted-tokens-jwe/jwe-loading.md)
* [Symfony Bundle](symfony-bundle/README.md)
  * [Algorithm Management](symfony-bundle/algorithm-management.md)
  * [Key and Key Set Management](symfony-bundle/key-and-key-set-management/README.md)
    * [Key Management \(JWK\)](symfony-bundle/key-and-key-set-management/key-management-jwk.md)
    * [Key Set Management \(JWKSet\)](symfony-bundle/key-and-key-set-management/key-set-management-jwkset.md)
  * [Header and Claim Checker Management](symfony-bundle/header-and-claim-checker-management.md)
  * [Signed Tokens](symfony-bundle/signed-tokens/README.md)
    * [JWS serializers](symfony-bundle/signed-tokens/jws-serializers.md)
    * [JWS creation](symfony-bundle/signed-tokens/jws-creation.md)
    * [JWS verification](symfony-bundle/signed-tokens/jws-verification.md)
  * [Encrypted Tokens](symfony-bundle/encrypted-tokens/README.md)
    * [JWE serializers](symfony-bundle/encrypted-tokens/jwe-serializers.md)
    * [JWE creation](symfony-bundle/encrypted-tokens/jwe-creation.md)
    * [JWE decryption](symfony-bundle/encrypted-tokens/jwe-decryption.md)
  * [Configuration Helper](symfony-bundle/configuration-helper.md)
* [Console](console/README.md)
  * [Standalone Application](console/standalone.md)
  * [Symfony Console](console/symfony-console.md)
  * [PHAR Application](console/phar-application.md)
* [Security Recommendations](security-recommendations.md)
* [Advanced Topics](advanced-topics/README.md)
  * [Nested Tokens](advanced-topics/nested-tokens.md)
  * [Serialization](advanced-topics/serialization.md)
  * [Custom Algorithm](advanced-topics/custom-algorithm.md)
  * Signed tokens and
    * [Unprotected Header](advanced-topics/signed-tokens-and/unprotected-header.md)
    * [Multiple Signatures](advanced-topics/signed-tokens-and/multiple-signatures.md)
    * [Detached Payload](advanced-topics/signed-tokens-and/detached-payload.md)
    * [Unencoded Payload](advanced-topics/signed-tokens-and/unencoded-payload.md)
  * Encrypted tokens and
    * [Unprotected Headers](advanced-topics/encrypted-tokens-and/unprotected-headers.md)
    * [Multiple Recipients](advanced-topics/encrypted-tokens-and/multiple-recipients.md)
    * [Additional Authentication Data \(AAD\)](advanced-topics/encrypted-tokens-and/additional-authentication-data-aad.md)
* [Benchmarks](benchmarks/README.md)
  * [Result table](benchmarks/result-table.md)
* [Migration](migration/README.md)
  * [From spomky-labs/jose](migration/from-spomky-labs-jose/README.md)
    * [Keys \(JWK\)](migration/from-spomky-labs-jose/keys-jwk.md)
    * [Key Sets \(JWKSet\)](migration/from-spomky-labs-jose/key-sets-jwkset.md)
    * [Signed Tokens \(JWS\)](migration/from-spomky-labs-jose/signed-tokens-jws.md)
    * [Encrypted Tokens \(JWE\)](migration/from-spomky-labs-jose/encrypted-tokens-jwe.md)
    * [Header Checking](migration/from-spomky-labs-jose/header-checking.md)
    * [Claim Checking](migration/from-spomky-labs-jose/claim-checking.md)

