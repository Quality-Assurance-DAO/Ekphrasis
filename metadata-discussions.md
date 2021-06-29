# Metadata Discussions

## Alessandro Konrad's CIP Proposal <a id="alessandro-konrads-proposal"></a>

{% embed url="https://forum.cardano.org/t/cip-nft-metadata-standard/45687" %}

## Native Tokens Q&A with Polina Vinogradova, lead engineer <a id="native-tokens-q-and-a-with-polina-vinogradova-lead-engineer"></a>

{% embed url="https://www.youtube.com/watch?v=ZSvfITJp7R0&t=22s" %}

### Notes <a id="notes"></a>

### Token features : <a id="token-features"></a>

Each Token has a :

Policy id

Asset name \(the unique index\)

A policy script dictates how the token is minted. A policy can include/combine time intervals and signatures.

Metadata is stored in a transaction's history not on the ledger

### Metadata server <a id="metadata-server"></a>

Metadata will be stored in JSON schema on a server.

Basic JSON schema will include :

Policy ID, Asset Name, Description, Logo, URL, Signatures required by policyID and Corresponding Keys

A token name can be registered more than once but not an asset name \(the unique index\)

Anyone will able to run their own metadata server with their own rules and standards.

### References

{% embed url="https://github.com/cardano-foundation/cardano-token-registry" %}

{% embed url="https://github.com/input-output-hk/cardano-metadata-submitter" %}



