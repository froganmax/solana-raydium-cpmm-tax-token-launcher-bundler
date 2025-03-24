# solana-raydium-cpmm-tax-token-launcher-bundler
## Contact
https://t.me/frogansol
## Test Example
calling create2022TokenWithMetadata..
calling generateMetadataUri..
image 
metadata {
  name: 'solana',
  symbol: 'solana',
  description: "it's description",
  image: ''
}
metadata {
  name: 'solana',
  symbol: 'solana',
  description: "it's description",
  image: '',
  extensions: {
    website: 'https://x.com',
    twitter: 'https://x.com',
    telegram: 'https://x.com'
  },
  tags: [ 'Meme', 'Tokenization' ]
}
(node:339341) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
Metadata uploaded: https://gateway.pinata.cloud/ipfs/Qmf4XU5Yx9bRsTGn6dRGVPzpoqCmFYsDYyz51JkfmZkG58
Token2022 is created: https://solscan.io/tx/2kAghu9g47cLgvdb3LJtywt3toiSx23BbaUzL1Ne7oBw3MuBwPTFGXGLoFEM17xZU8PdHDtN93Z8qZ6meoyvq1Yy?cluster=devnet
Token2022 contract link: https://solscan.io/token/HJDkQLrWttnx18LJ5RdWEVTyCSKgc9M3cdpuN4AhNWx1?cluster=devnet
mint, amount PublicKey [PublicKey(HJDkQLrWttnx18LJ5RdWEVTyCSKgc9M3cdpuN4AhNWx1)] {
  _bn: <BN: f22447760f98aa0bf12183312ed51fe1abaaf3d919f590ced776c662f2ac2d32>
} 1000000000000n
tokenResult {
  mint: PublicKey [PublicKey(HJDkQLrWttnx18LJ5RdWEVTyCSKgc9M3cdpuN4AhNWx1)] {
    _bn: <BN: f22447760f98aa0bf12183312ed51fe1abaaf3d919f590ced776c662f2ac2d32>
  },
  amount: 1000000000000n
}
Wrapped SOL transaction: https://solscan.io/tx/4hgBhPed46tgnpL7FfDw37YqHTwUJ34fCqeNLnEbKF9J1sJBb6w5b69RkVxZxA5n28pyCmxhkzv9imvgHn4i7EM9


========================== Creating CPMM pool =========================

connect to rpc https://devnet.helius-rpc.com/?api-key=f3c02a35-f460-48c5-95ac-392942fc621d in devnet
info  {
  poolId: PublicKey [PublicKey(Bay3ajnN94xpy58p3FXNZL783Q1okmU8rg4sY9eFfJyu)] {
    _bn: <BN: 9d4867db9828af2e7ff4cbe810c3c5ef79d4be200e4a2d8f08a795dda87370b8>
  },
  configId: PublicKey [PublicKey(9zSzfkYy6awexsHvmggeH36pfVUdDGyCcwmjT3AQPBj6)] {
    _bn: <BN: 8594fe4c4e34cef78fbf99c1c49fbf834bbf7fc89d36115c28476a4e8348faf1>
  },
  authority: PublicKey [PublicKey(7rQ1QFNosMkUCuh7Z7fPbTHvh73b68sQYdirycEzJVuw)] {
    _bn: <BN: 65cd985f02a93c6a9d0c1c82c037ba621e302f4a5666f5af6be37f50a37c1406>
  },
  lpMint: PublicKey [PublicKey(Hy3z933yUsuaLvn35v9gjawzE2JTe2XUFKdsTP5tNijL)] {
    _bn: <BN: fc16e435d8340c0fa18ad18d94f1d74fb1a1c003a03daf2802aa50ab7a4916d3>
  },
  vaultA: PublicKey [PublicKey(9FoghApPymbTQ6JKDUyPGfkfFUQopeQ1enXnmDCAcN8y)] {
    _bn: <BN: 7aa869b435ab8da109ffb0302a1cdedeacad82e3130cc5d2c5c439b4a0151aaa>
  },
  vaultB: PublicKey [PublicKey(4p7S8y9Df8LqEtwxakxCCJcsZfrH9ZZEhLo5k1LANg4P)] {
    _bn: <BN: 38a4a21160430bf24bab729ca64945e98d7ebf6953a58ae13859003d232de678>
  },
  observationId: PublicKey [PublicKey(GN2tEKrkLr8Q2kvWjxXRqBbWPVH4BXHczXx3sPHgcNzm)] {
    _bn: <BN: e442a15bd7eeaba8e66d6a0d15aa8d373d713135e4dc62168b07ae432ad4ea72>
  },
  mintA: {
    chainId: 101,
    address: 'So11111111111111111111111111111111111111112',
    programId: 'TokenkegQfeZyiNwAJbNbGKPFXCWuBvf9Ss623VQ5DA',
    logoURI: 'https://img-v1.raydium.io/icon/So11111111111111111111111111111111111111112.png',
    symbol: 'WSOL',
    name: 'Wrapped SOL',
    decimals: 9,
    tags: [],
    extensions: {},
    type: 'raydium',
    priority: 2
  },
  mintB: {
    chainId: 101,
    address: 'HJDkQLrWttnx18LJ5RdWEVTyCSKgc9M3cdpuN4AhNWx1',
    programId: 'TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb',
    logoURI: '',
    symbol: 'HJDkQL',
    name: 'HJDkQL',
    decimals: 6,
    tags: [],
    extensions: {},
    priority: 0,
    type: 'unknown'
  },
  programId: PublicKey [PublicKey(CPMDWBwJDtYax9qW7AyRuVC19Cc4L4Vcy4n2BHAbHkCW)] {
    _bn: <BN: a92a311a8898864d2063c8fccb536e1e8a304d8d53984c0a4eb3c14407d674e7>
  },
  poolFeeAccount: PublicKey [PublicKey(G11FKBRaAkHAKuLCgLM6K6NUc9rTjPAznRCjZifrTQe2)] {
    _bn: <BN: dedf953b2e71837bb572ab091421997463fa9f21967cc2f503201e8415b3e4bf>
  },
  feeConfig: {
    id: '9zSzfkYy6awexsHvmggeH36pfVUdDGyCcwmjT3AQPBj6',
    index: 0,
    protocolFeeRate: 120000,
    tradeFeeRate: 2500,
    fundFeeRate: 40000,
    createPoolFee: '150000000'
  }
}
simulate tx string: [
  'AagGL2q5BINNy/+A084TkQ6YZcYzunywJ4uvNMIEBkFHcB6V4I2l7s1Uj9XYAT+4CLDzEPldkhHxH2r3A5TPVwyAAQALFaO4FlaFeJzCI/St/7nHNZLrxfCpqblz9MBIe5LUAbQdM3BWBNjmoNx7Aw9wTQkEO8UlUKWLtwwTtO4jfImmAT+dSGfbmCivLn/0y+gQw8XvedS+IA5KLY8Ip5XdqHNwuPwW5DXYNAwPoYrRjZTx10+xocADoD2vKAKqUKt6SRbTJ88ZqmUHDR5sXvkWnpM1S7EyNCncBpKa+P1dE0sz9LAbWxjSJIP7WrWr+FyGUgeGXN9oP5Hsg3H1xBKDqhZJH3qoabQ1q42hCf+wMCoc3t6srYLjEwzF0sXEObSgFRqqOKSiEWBDC/JLq3KcpklF6Y1+v2lTpYrhOFkAPSMt5nje35U7LnGDe7VyqwkUIZl0Y/qfIZZ8wvUDIB6EFbPkv+RCoVvX7quo5m1qDRWqjTc9cTE15NxiFosHrkMq1OpyAwZGb+UhFzL/7K26csOb57yM5bvF9xJrLEObOkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAbd9uHXZaGT2cvhRs7reawctIXtX1s3kTqM9YV+/wCpBpuIV/6rgYT7aH9jRhjANdrEOdwa6ztVmKDwAAAAAAEGp9UXGSxcUSGMyUw9SvF/WNruCJuh/UTj29mKAAAAAKkqMRqImIZNIGPI/MtTbh6KME2NU5hMCk6zwUQH1nTnhZT+TE40zvePv5nBxJ+/g0u/f8idNhFcKEdqToNI+vFlzZhfAqk8ap0MHILAN7piHjAvSlZm9a9r439Qo3wUBvIkR3YPmKoL8SGDMS7VH+GrqvPZGfWQztd2xmLyrC0yBt324e51j94YQl285GzN2rYa/E2DuQ0n/r35KNihi/yMlyWPTiSJ8bs9ECkUjg2DC1oTmdr/EIQEjnvY2+n4WZ0NLkQ3wkp1q8A/j4Xn7T/MsMQaz9RSjkrHcJUzNLLVBgoACQOghgEAAAAAAAoABQLgkwQACwIAAXwDAAAAo7gWVoV4nMIj9K3/ucc1kuvF8KmpuXP0wEh7ktQBtB0gAAAAAAAAAEFxbm51THk1WHhYUENLV0thQ0c4d20yanFBMVQ5a0NhkKQgAAAAAAClAAAAAAAAAAbd9uHXZaGT2cvhRs7reawctIXtX1s3kTqM9YV+/wCpDAQBDQAOAQEPFAAQEQINEgMBBAUGBwgJDAwTFAsOIK+vbR8NmJvtoIYBAAAAAAAAEKXU6AAAAAAAAAAAAAAADAMBAAABCQA='
]
CPMM pool created : https://solscan.io/tx/4MqpmirJdyhrUJzPK3DrvZMD32wzdk3Lg4DHViSkSri4JEcrHmAGFhxx6ZxgEmsFTQDGWkVNqb3kQdnGv17vRBL7?cluster=devnet


===============  Simulating buys and transfers from users, since it is on devnet  ===========
