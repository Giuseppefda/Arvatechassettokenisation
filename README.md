# Arvatechassettokenisation
https://github.com/Giuseppefda/Arvatechassettokenisation.git
The constructor function mints three different types of tokens (in the sample code: GOLD, SILVER, and BRONZE) to the contract deployer's address. The mint function can be used by the owner to mint additional tokens, while the burn function allows for tokens to be burned (destroyed) by either the owner or the account that owns the tokens.
The uri function is overridden to append the ".json" extension to the base URI defined in the constructor, allowing for metadata to be fetched for each token ID.
