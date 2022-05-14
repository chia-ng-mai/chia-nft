
![Ping River](https://raw.githubusercontent.com/chia-ng-mai/chia-nft/a219e1144f6b3b4ca06737452f82b1aa9cdcdced/assets/ping_river.jpg)

# sha256sum

```sh
❯ curl -s https://raw.githubusercontent.com/chia-ng-mai/chia-nft/a219e1144f6b3b4ca06737452f82b1aa9cdcdced/assets/ping_river.jpg | sha256sum
ea1f6514d221e5b8b7f0fdff7a4da8802448da111b2beed32d2975f29f362dc2  -
```

# nft_mint_nft ([mint-ping-river.json](mint-ping-river.json))

```sh
❯ chia rpc wallet nft_mint_nft -j ./mint-ping-river.json
{
    "spend_bundle": {
        "aggregated_signature": "0xa4ba748cdfcee458f905fdeb2d597e3e368ea95906ab63aaeca9d30c8f6014e13286139037c1ab1dc4c9f2d5a2cc5be4066c61753a528a55bee76fa6800360e47520ebe0aa2000dadd6399e91b5801a387b05bb509a213add6845f12bfeb8b06",
        "coin_solutions": [
            {
                "coin": {
                    "amount": 999999999998,
                    "parent_coin_info": "0xbe754b7f2b3b7cece6260e1c32f8391db5c03ffaf1b44f40725095c2545e9d4d",
                    "puzzle_hash": "0x59f1526ef666fe92156996fad7b3979e80945949a45472049f31ce42b1aadb94"
                },
                "puzzle_reveal": "0xff02ffff01ff02ffff01ff02ffff03ff0bffff01ff02ffff03ffff09ff05ffff1dff0bffff1effff0bff0bffff02ff06ffff04ff02ffff04ff17ff8080808080808080ffff01ff02ff17ff2f80ffff01ff088080ff0180ffff01ff04ffff04ff04ffff04ff05ffff04ffff02ff06ffff04ff02ffff04ff17ff80808080ff80808080ffff02ff17ff2f808080ff0180ffff04ffff01ff32ff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff06ffff04ff02ffff04ff09ff80808080ffff02ff06ffff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff018080ffff04ffff01b0a32fa409138f4088bb26e08d065172ddb1db4bdbee9809d688fb7dc40ade4a8776db49584299786105600f3310eb473eff018080",
                "solution": "0xff80ffff01ffff33ffa0eff07522495060c066f66f32acc2a77e3a3e737aca8baea4d1a64ea4cdc13da9ff0180ffff33ffa0721546119728271b3ee362cdae39f1d9296008e84160c14d8ab7d60b7fff73e8ff8600e8d4a50ffd80ffff3cffa0a4b776c1f706c9b21a35f22e95ec657cc628e23606b6fc03b431d82f064e741680ffff3dffa0ceb6fb8deea0659bc8731cebce5d4bd1bd3801abdabaeec6083cacb86c565feb8080ff8080"
            },
            {
                "coin": {
                    "amount": 1,
                    "parent_coin_info": "0xa59f91a4189e871dc13aaf2ab46aa747be12643525b599e2b94543fcfdb7a7b7",
                    "puzzle_hash": "0xda15e625cefe4c605f02c21b2b244766f746e025d0743bc3ac91f298befa414c"
                },
                "puzzle_reveal": "0xff02ffff01ff02ffff01ff02ffff03ffff18ff2fff3c80ffff01ff04ffff04ff10ffff04ff2fff808080ffff04ffff02ff3effff04ff02ffff04ff05ffff04ffff0bff27ffff02ffff03ff77ffff01ff02ff36ffff04ff02ffff04ff09ffff04ff57ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ffff011d80ff0180ffff02ffff03ff77ffff0181b7ffff015780ff018080ffff04ff77ff808080808080ffff02ff26ffff04ff02ffff04ff05ffff04ffff02ff0bff5f80ffff01ff8080808080808080ffff01ff088080ff0180ffff04ffff01ffffff49ff4702ff33ff0401ffff01ff02ff02ffff03ff05ffff01ff02ff3affff04ff02ffff04ff0dffff04ffff0bff2affff0bff3cff2c80ffff0bff2affff0bff2affff0bff3cff1280ff0980ffff0bff2aff0bffff0bff3cff8080808080ff8080808080ffff010b80ff0180ffffff02ffff03ff0bffff01ff02ffff03ffff02ffff03ffff09ff23ff1480ffff01ff02ffff03ffff18ff81b3ff3c80ffff01ff0101ff8080ff0180ff8080ff0180ffff01ff02ffff03ffff20ff1780ffff01ff02ffff03ffff09ff81b3ffff01818f80ffff01ff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff808080808080ffff01ff04ffff04ff23ffff04ffff02ff36ffff04ff02ffff04ff09ffff04ff53ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ff738080ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff8080808080808080ff0180ffff01ff088080ff0180ffff01ff04ff13ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff17ff8080808080808080ff0180ffff01ff02ffff03ff17ff80ffff01ff088080ff018080ff0180ff0bff2affff0bff3cff3880ffff0bff2affff0bff2affff0bff3cff1280ff0580ffff0bff2affff02ff3affff04ff02ffff04ff07ffff04ffff0bff3cff3c80ff8080808080ffff0bff3cff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bff3cff058080ff0180ff02ffff03ffff21ff17ffff09ff0bff158080ffff01ff04ff28ffff04ff0bff808080ffff01ff088080ff0180ff018080ffff04ffff01ffa0f1e8350cec62f8204aaf867cc3c12cae369f619258206616108c6cfd7be760b3ffa0a59f91a4189e871dc13aaf2ab46aa747be12643525b599e2b94543fcfdb7a7b7a0eff07522495060c066f66f32acc2a77e3a3e737aca8baea4d1a64ea4cdc13da9ffff04ffff01ff02ffff01ff02ffff01ff04ffff04ff10ffff04ff81bfff808080ffff02ff3effff04ff02ffff04ff05ffff04ffff02ff3affff04ff02ffff04ff17ffff04ff0bffff04ffff02ff2fff5f80ff808080808080ffff04ff81bfffff01ff8080808080808080ffff04ffff01ffffff49ff0233ffff0401ff0102ffffffff02ffff03ff05ffff01ff02ff22ffff04ff02ffff04ff0dffff04ffff0bff3cffff0bff34ff2480ffff0bff3cffff0bff3cffff0bff34ff2c80ff0980ffff0bff3cff0bffff0bff34ff8080808080ff8080808080ffff010b80ff0180ff02ffff03ff17ffff01ff02ffff03ffff09ff47ffff0181e880ffff01ff02ffff03ffff09ffff02ff2effff04ff02ffff04ff81a7ff80808080ff0580ffff01ff02ff81a7ffff04ff0bffff04ff05ffff04ff820167ff8080808080ffff01ff088080ff0180ffff01ff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff37ff80808080808080ff0180ffff01ff04ffff04ff0bffff04ff05ff808080ffff01ff80808080ff0180ffff02ffff03ff05ffff01ff04ff09ffff02ff2affff04ff02ffff04ff0dffff04ff0bff808080808080ffff010b80ff0180ff02ff26ffff04ff02ffff04ffff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff17ff808080808080ffff04ff17ff8080808080ffffff04ff09ffff04ffff02ff2affff04ff02ffff04ff15ffff04ff0bff8080808080ff808080ff0bff3cffff0bff34ff2880ffff0bff3cffff0bff3cffff0bff34ff2c80ff0580ffff0bff3cffff02ff22ffff04ff02ffff04ff07ffff04ffff0bff34ff3480ff8080808080ffff0bff34ff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff02ffff03ff2bffff01ff02ffff03ffff09ff818bff3880ffff01ff02ffff03ffff18ff8202cbff3480ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff4bff80808080808080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff808080808080808080ff0180ffff01ff02ffff03ffff15ff818bff8080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ff018080ff0180ffff01ff02ffff03ff2fffff01ff04ffff04ff38ffff04ffff02ff36ffff04ff02ffff04ff05ffff04ff81afffff04ffff0bff34ff5380ffff04ffff02ff2effff04ff02ffff04ff23ff80808080ffff04ffff0bff34ff0580ff8080808080808080ffff04ff17ff8201ef808080ff8080ffff01ff088080ff018080ff0180ff018080ffff04ffff01a0dd8135d546e291df295b376aa89fc409c8c50d7f655d1ff4e845637901bc2f8fffff04ffff01ffff75ffc07568747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f636869612d6e672d6d61692f636869612d6e66742f613231396531313434663662336234636130363733373435326638326231616139636463646365642f6173736574732f70696e675f72697665722e6a706780ffff68a0ea1f6514d221e5b8b7f0fdff7a4da8802448da111b2beed32d2975f29f362dc280ffff04ffff01a081970d352e6a39a241eaf8ca510a0e669e40d778ba612621c60a50ef6cf29c7bffff04ffff01ff02ffff01ff02ffff01ff02ffff03ff0bffff01ff02ffff03ffff09ff05ffff1dff0bffff1effff0bff0bffff02ff06ffff04ff02ffff04ff17ff8080808080808080ffff01ff02ff17ff2f80ffff01ff088080ff0180ffff01ff04ffff04ff04ffff04ff05ffff04ffff02ff06ffff04ff02ffff04ff17ff80808080ff80808080ffff02ff17ff2f808080ff0180ffff04ffff01ff32ff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff06ffff04ff02ffff04ff09ff80808080ffff02ff06ffff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff018080ffff04ffff01b0ae4153be598dd32bb7e197fd803cb257a20c27a26fb8c211fa32cd9826061b525fd9e9b43a239562548de38fcc74ab06ff018080ff018080808080ff01808080",
                "solution": "0xffffa0b9495ca7236db7fdf7e31ced35f2bb98e2e9093c7d519c1d99ab062ca6174a97ff0180ff01ffffff80ffff01ffff33ffa02e6a3f119a9b75cb2599830142cb77db247633403563c14bce680c042de6c0d9ff01ff808080ff8080ff01ff808080"
            },
            {
                "coin": {
                    "amount": 1,
                    "parent_coin_info": "0xb9495ca7236db7fdf7e31ced35f2bb98e2e9093c7d519c1d99ab062ca6174a97",
                    "puzzle_hash": "0xeff07522495060c066f66f32acc2a77e3a3e737aca8baea4d1a64ea4cdc13da9"
                },
                "puzzle_reveal": "0xff02ffff01ff04ffff04ff04ffff04ff05ffff04ff0bff80808080ffff04ffff04ff0affff04ffff02ff0effff04ff02ffff04ffff04ff05ffff04ff0bffff04ff17ff80808080ff80808080ff808080ff808080ffff04ffff01ff33ff3cff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff0effff04ff02ffff04ff09ff80808080ffff02ff0effff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff018080",
                "solution": "0xffa0da15e625cefe4c605f02c21b2b244766f746e025d0743bc3ac91f298befa414cff01ff8080"
            }
        ]
    },
    "success": true,
    "wallet_id": 2
}
```

# nft_get_nfts

```sh
❯ chia rpc wallet nft_get_nfts '{\"wallet_id\": 2}'
{
    "nft_list": [
        {
            "data_hash": "4584253A77E18E508749DDE0174C3519E8F6C71482D30E408C419641BF407322",
            "data_uris": [
                "https://pbs.twimg.com/profile_banners/1481826219242971142/1642132427/1500x500"
            ],
            "did_owner": "",
            "edition_count": 1,
            "edition_number": 1,
            "launcher_id": "6A6A7E6599DEC85798999AAFC52B7F5A5DB86643953D3DEDE9604821A2BA2199",
            "license_hash": "",
            "license_uris": [],
            "metadata_hash": "",
            "metadata_uris": [],
            "nft_coin_id": "90F02A811BCE3748FFC794256AF5DC672EE52CB11C9D767887C7336201BB01B2",
            "royalty": 0,
            "version": "NFT0"
        },
        {
            "data_hash": "EA1F6514D221E5B8B7F0FDFF7A4DA8802448DA111B2BEED32D2975F29F362DC2",
            "data_uris": [
                "https://raw.githubusercontent.com/chia-ng-mai/chia-nft/a219e1144f6b3b4ca06737452f82b1aa9cdcdced/assets/ping_river.jpg"
            ],
            "did_owner": "",
            "edition_count": 1,
            "edition_number": 1,
            "launcher_id": "A59F91A4189E871DC13AAF2AB46AA747BE12643525B599E2B94543FCFDB7A7B7",
            "license_hash": "",
            "license_uris": [],
            "metadata_hash": "",
            "metadata_uris": [],
            "nft_coin_id": "F3A9C9AD5AFDC9D0997E4DB6071A2475455302B9DD89CCFFBACD316196106A73",
            "royalty": 0,
            "version": "NFT0"
        }
    ],
    "success": true,
    "wallet_id": 2
}
```

# nft_add_uri ([add-uri-ping-river.json](add-uri-ping-river.json))

```sh
❯ chia rpc wallet nft_add_uri -j ./add-uri-ping-river.json
{
    "spend_bundle": {
        "aggregated_signature": "0x8ca6b7c22006678e3baba3360802694c03ab4053b03e4eabc3ccb5c4c1739155b8146fdeb16d108e4f4b5130ad60e4e516cdcf953be29b94d339644645dbaa00d68e9e7d2c963cfd852f2adea8bc263287d10fa25ed13e1ef9192debedf09ad9",
        "coin_solutions": [
            {
                "coin": {
                    "amount": 1,
                    "parent_coin_info": "0xf562d82f26b8d2e5daea583bc099ba76a32cb82a40955daca30f105bba3186e4",
                    "puzzle_hash": "0xbb72ad1a821cd3b14050f6b8b810d827f3488c62f2b868b211f873f1a5c85e87"
                },
                "puzzle_reveal": "0xff02ffff01ff02ffff01ff02ffff03ffff18ff2fff3c80ffff01ff04ffff04ff10ffff04ff2fff808080ffff04ffff02ff3effff04ff02ffff04ff05ffff04ffff0bff27ffff02ffff03ff77ffff01ff02ff36ffff04ff02ffff04ff09ffff04ff57ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ffff011d80ff0180ffff02ffff03ff77ffff0181b7ffff015780ff018080ffff04ff77ff808080808080ffff02ff26ffff04ff02ffff04ff05ffff04ffff02ff0bff5f80ffff01ff8080808080808080ffff01ff088080ff0180ffff04ffff01ffffff49ff4702ff33ff0401ffff01ff02ff02ffff03ff05ffff01ff02ff3affff04ff02ffff04ff0dffff04ffff0bff2affff0bff3cff2c80ffff0bff2affff0bff2affff0bff3cff1280ff0980ffff0bff2aff0bffff0bff3cff8080808080ff8080808080ffff010b80ff0180ffffff02ffff03ff0bffff01ff02ffff03ffff02ffff03ffff09ff23ff1480ffff01ff02ffff03ffff18ff81b3ff3c80ffff01ff0101ff8080ff0180ff8080ff0180ffff01ff02ffff03ffff20ff1780ffff01ff02ffff03ffff09ff81b3ffff01818f80ffff01ff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff808080808080ffff01ff04ffff04ff23ffff04ffff02ff36ffff04ff02ffff04ff09ffff04ff53ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ff738080ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff8080808080808080ff0180ffff01ff088080ff0180ffff01ff04ff13ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff17ff8080808080808080ff0180ffff01ff02ffff03ff17ff80ffff01ff088080ff018080ff0180ff0bff2affff0bff3cff3880ffff0bff2affff0bff2affff0bff3cff1280ff0580ffff0bff2affff02ff3affff04ff02ffff04ff07ffff04ffff0bff3cff3c80ff8080808080ffff0bff3cff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bff3cff058080ff0180ff02ffff03ffff21ff17ffff09ff0bff158080ffff01ff04ff28ffff04ff0bff808080ffff01ff088080ff0180ff018080ffff04ffff01ffa0f1e8350cec62f8204aaf867cc3c12cae369f619258206616108c6cfd7be760b3ffa0a59f91a4189e871dc13aaf2ab46aa747be12643525b599e2b94543fcfdb7a7b7a0eff07522495060c066f66f32acc2a77e3a3e737aca8baea4d1a64ea4cdc13da9ffff04ffff01ff02ffff01ff02ffff01ff04ffff04ff10ffff04ff81bfff808080ffff02ff3effff04ff02ffff04ff05ffff04ffff02ff3affff04ff02ffff04ff17ffff04ff0bffff04ffff02ff2fff5f80ff808080808080ffff04ff81bfffff01ff8080808080808080ffff04ffff01ffffff49ff0233ffff0401ff0102ffffffff02ffff03ff05ffff01ff02ff22ffff04ff02ffff04ff0dffff04ffff0bff3cffff0bff34ff2480ffff0bff3cffff0bff3cffff0bff34ff2c80ff0980ffff0bff3cff0bffff0bff34ff8080808080ff8080808080ffff010b80ff0180ff02ffff03ff17ffff01ff02ffff03ffff09ff47ffff0181e880ffff01ff02ffff03ffff09ffff02ff2effff04ff02ffff04ff81a7ff80808080ff0580ffff01ff02ff81a7ffff04ff0bffff04ff05ffff04ff820167ff8080808080ffff01ff088080ff0180ffff01ff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff37ff80808080808080ff0180ffff01ff04ffff04ff0bffff04ff05ff808080ffff01ff80808080ff0180ffff02ffff03ff05ffff01ff04ff09ffff02ff2affff04ff02ffff04ff0dffff04ff0bff808080808080ffff010b80ff0180ff02ff26ffff04ff02ffff04ffff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff17ff808080808080ffff04ff17ff8080808080ffffff04ff09ffff04ffff02ff2affff04ff02ffff04ff15ffff04ff0bff8080808080ff808080ff0bff3cffff0bff34ff2880ffff0bff3cffff0bff3cffff0bff34ff2c80ff0580ffff0bff3cffff02ff22ffff04ff02ffff04ff07ffff04ffff0bff34ff3480ff8080808080ffff0bff34ff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff02ffff03ff2bffff01ff02ffff03ffff09ff818bff3880ffff01ff02ffff03ffff18ff8202cbff3480ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff4bff80808080808080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff808080808080808080ff0180ffff01ff02ffff03ffff15ff818bff8080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ff018080ff0180ffff01ff02ffff03ff2fffff01ff04ffff04ff38ffff04ffff02ff36ffff04ff02ffff04ff05ffff04ff81afffff04ffff0bff34ff5380ffff04ffff02ff2effff04ff02ffff04ff23ff80808080ffff04ffff0bff34ff0580ff8080808080808080ffff04ff17ff8201ef808080ff8080ffff01ff088080ff018080ff0180ff018080ffff04ffff01a0dd8135d546e291df295b376aa89fc409c8c50d7f655d1ff4e845637901bc2f8fffff04ffff01ffff75ffc07568747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f636869612d6e672d6d61692f636869612d6e66742f613231396531313434663662336234636130363733373435326638326231616139636463646365642f6173736574732f70696e675f72697665722e6a706780ffff68a0ea1f6514d221e5b8b7f0fdff7a4da8802448da111b2beed32d2975f29f362dc280ffff04ffff01a081970d352e6a39a241eaf8ca510a0e669e40d778ba612621c60a50ef6cf29c7bffff04ffff01ff02ffff01ff02ffff01ff02ffff03ff0bffff01ff02ffff03ffff09ff05ffff1dff0bffff1effff0bff0bffff02ff06ffff04ff02ffff04ff17ff8080808080808080ffff01ff02ff17ff2f80ffff01ff088080ff0180ffff01ff04ffff04ff04ffff04ff05ffff04ffff02ff06ffff04ff02ffff04ff17ff80808080ff80808080ffff02ff17ff2f808080ff0180ffff04ffff01ff32ff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff06ffff04ff02ffff04ff09ff80808080ffff02ff06ffff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff018080ffff04ffff01b096e1ea469479e408076f2b585b86c579c2a34cb1a47f543ad4867a8eba4e0cd30dbfee4c1b76e1e90c3ec72972a7ad7eff018080ff018080808080ff01808080",
                "solution": "0xffffa0a59f91a4189e871dc13aaf2ab46aa747be12643525b599e2b94543fcfdb7a7b7ffa08803b909eef74b0aee807697737efc763328f49d4f9129f9180a32ed93d65aaeff0180ff01ffffff80ffff01ffff33ffa02e6a3f119a9b75cb2599830142cb77db247633403563c14bce680c042de6c0d9ff01ffffa02e6a3f119a9b75cb2599830142cb77db247633403563c14bce680c042de6c0d98080ffff81e8ffff02ffff01ff04ffff04ffff02ffff03ff17ffff01ff02ff02ffff04ff02ffff04ff05ffff04ff17ff8080808080ffff010580ff0180ffff04ff0bff808080ffff01ff808080ffff04ffff01ff02ffff03ff05ffff01ff02ffff03ffff09ff11ffff017580ffff01ff04ffff04ffff0175ffff04ff0bff198080ff0d80ffff01ff04ff09ffff02ff02ffff04ff02ffff04ff0dffff04ff0bff80808080808080ff0180ff8080ff0180ff018080ffc05168747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f636869612d6e672d6d61692f636869612d6e66742f6d61696e2f6173736574732f70696e675f72697665722e6a70678080ff8080ff01ff808080"
            }
        ]
    },
    "success": true,
    "wallet_id": 2
}

❯ chia rpc wallet nft_get_nfts '{\"wallet_id\": 2}'
{
    "nft_list": [
        {
            "data_hash": "4584253A77E18E508749DDE0174C3519E8F6C71482D30E408C419641BF407322",
            "data_uris": [
                "https://pbs.twimg.com/profile_banners/1481826219242971142/1642132427/1500x500"
            ],
            "did_owner": "",
            "edition_count": 1,
            "edition_number": 1,
            "launcher_id": "6A6A7E6599DEC85798999AAFC52B7F5A5DB86643953D3DEDE9604821A2BA2199",
            "license_hash": "",
            "license_uris": [],
            "metadata_hash": "",
            "metadata_uris": [],
            "nft_coin_id": "90F02A811BCE3748FFC794256AF5DC672EE52CB11C9D767887C7336201BB01B2",
            "royalty": 0,
            "version": "NFT0"
        },
        {
            "data_hash": "EA1F6514D221E5B8B7F0FDFF7A4DA8802448DA111B2BEED32D2975F29F362DC2",
            "data_uris": [
                "https://raw.githubusercontent.com/chia-ng-mai/chia-nft/main/assets/ping_river.jpg",
                "https://raw.githubusercontent.com/chia-ng-mai/chia-nft/a219e1144f6b3b4ca06737452f82b1aa9cdcdced/assets/ping_river.jpg"
            ],
            "did_owner": "",
            "edition_count": 1,
            "edition_number": 1,
            "launcher_id": "A59F91A4189E871DC13AAF2AB46AA747BE12643525B599E2B94543FCFDB7A7B7",
            "license_hash": "",
            "license_uris": [],
            "metadata_hash": "",
            "metadata_uris": [],
            "nft_coin_id": "8A206D5ADECA843B245A8BC9F49605348BC5281D0C4944AD971F6695BE6A6249",
            "royalty": 0,
            "version": "NFT0"
        }
    ],
    "success": true,
    "wallet_id": 2
}
```

# nft_transfer_nft ([transfer-ping-river.json](transfer-ping-river.json))

```sh
❯ chia rpc wallet nft_transfer_nft -j ./transfer-ping-river.json
{
    "spend_bundle": {
        "aggregated_signature": "0xb890770073809cced1a1fe639d675673ea571f6acb089cd2e8e9ad216381be37f3efbf58123a3e1ac7c4c2c2e8944147069aafe1efeb4059da71ab805af7099bf454bac7f86f123bcdb46875f7dcef3bd9483aa3b20910c0a7eb0d380ccbc161",
        "coin_solutions": [
            {
                "coin": {
                    "amount": 1,
                    "parent_coin_info": "0xf3a9c9ad5afdc9d0997e4db6071a2475455302b9dd89ccffbacd316196106a73",
                    "puzzle_hash": "0x470eb45826f98641f24aade374d583d8e2da58594fbb83e741a2773c67e4722e"
                },
                "puzzle_reveal": "0xff02ffff01ff02ffff01ff02ffff03ffff18ff2fff3c80ffff01ff04ffff04ff10ffff04ff2fff808080ffff04ffff02ff3effff04ff02ffff04ff05ffff04ffff0bff27ffff02ffff03ff77ffff01ff02ff36ffff04ff02ffff04ff09ffff04ff57ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ffff011d80ff0180ffff02ffff03ff77ffff0181b7ffff015780ff018080ffff04ff77ff808080808080ffff02ff26ffff04ff02ffff04ff05ffff04ffff02ff0bff5f80ffff01ff8080808080808080ffff01ff088080ff0180ffff04ffff01ffffff49ff4702ff33ff0401ffff01ff02ff02ffff03ff05ffff01ff02ff3affff04ff02ffff04ff0dffff04ffff0bff2affff0bff3cff2c80ffff0bff2affff0bff2affff0bff3cff1280ff0980ffff0bff2aff0bffff0bff3cff8080808080ff8080808080ffff010b80ff0180ffffff02ffff03ff0bffff01ff02ffff03ffff02ffff03ffff09ff23ff1480ffff01ff02ffff03ffff18ff81b3ff3c80ffff01ff0101ff8080ff0180ff8080ff0180ffff01ff02ffff03ffff20ff1780ffff01ff02ffff03ffff09ff81b3ffff01818f80ffff01ff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff808080808080ffff01ff04ffff04ff23ffff04ffff02ff36ffff04ff02ffff04ff09ffff04ff53ffff04ffff02ff2effff04ff02ffff04ff05ff80808080ff808080808080ff738080ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff3cff8080808080808080ff0180ffff01ff088080ff0180ffff01ff04ff13ffff02ff26ffff04ff02ffff04ff05ffff04ff1bffff04ff17ff8080808080808080ff0180ffff01ff02ffff03ff17ff80ffff01ff088080ff018080ff0180ff0bff2affff0bff3cff3880ffff0bff2affff0bff2affff0bff3cff1280ff0580ffff0bff2affff02ff3affff04ff02ffff04ff07ffff04ffff0bff3cff3c80ff8080808080ffff0bff3cff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bff3cff058080ff0180ff02ffff03ffff21ff17ffff09ff0bff158080ffff01ff04ff28ffff04ff0bff808080ffff01ff088080ff0180ff018080ffff04ffff01ffa0f1e8350cec62f8204aaf867cc3c12cae369f619258206616108c6cfd7be760b3ffa0a59f91a4189e871dc13aaf2ab46aa747be12643525b599e2b94543fcfdb7a7b7a0eff07522495060c066f66f32acc2a77e3a3e737aca8baea4d1a64ea4cdc13da9ffff04ffff01ff02ffff01ff02ffff01ff04ffff04ff10ffff04ff81bfff808080ffff02ff3effff04ff02ffff04ff05ffff04ffff02ff3affff04ff02ffff04ff17ffff04ff0bffff04ffff02ff2fff5f80ff808080808080ffff04ff81bfffff01ff8080808080808080ffff04ffff01ffffff49ff0233ffff0401ff0102ffffffff02ffff03ff05ffff01ff02ff22ffff04ff02ffff04ff0dffff04ffff0bff3cffff0bff34ff2480ffff0bff3cffff0bff3cffff0bff34ff2c80ff0980ffff0bff3cff0bffff0bff34ff8080808080ff8080808080ffff010b80ff0180ff02ffff03ff17ffff01ff02ffff03ffff09ff47ffff0181e880ffff01ff02ffff03ffff09ffff02ff2effff04ff02ffff04ff81a7ff80808080ff0580ffff01ff02ff81a7ffff04ff0bffff04ff05ffff04ff820167ff8080808080ffff01ff088080ff0180ffff01ff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff37ff80808080808080ff0180ffff01ff04ffff04ff0bffff04ff05ff808080ffff01ff80808080ff0180ffff02ffff03ff05ffff01ff04ff09ffff02ff2affff04ff02ffff04ff0dffff04ff0bff808080808080ffff010b80ff0180ff02ff26ffff04ff02ffff04ffff02ff32ffff04ff02ffff04ff05ffff04ff0bffff04ff17ff808080808080ffff04ff17ff8080808080ffffff04ff09ffff04ffff02ff2affff04ff02ffff04ff15ffff04ff0bff8080808080ff808080ff0bff3cffff0bff34ff2880ffff0bff3cffff0bff3cffff0bff34ff2c80ff0580ffff0bff3cffff02ff22ffff04ff02ffff04ff07ffff04ffff0bff34ff3480ff8080808080ffff0bff34ff8080808080ffff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff2effff04ff02ffff04ff09ff80808080ffff02ff2effff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff02ffff03ff2bffff01ff02ffff03ffff09ff818bff3880ffff01ff02ffff03ffff18ff8202cbff3480ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff4bff80808080808080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff808080808080808080ff0180ffff01ff02ffff03ffff15ff818bff8080ffff01ff04ff4bffff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ffff01ff02ff3effff04ff02ffff04ff05ffff04ffff04ffff04ff23ffff04ff53ff808080ffff04ff6bff808080ffff04ff17ffff04ff2fff8080808080808080ff018080ff0180ffff01ff02ffff03ff2fffff01ff04ffff04ff38ffff04ffff02ff36ffff04ff02ffff04ff05ffff04ff81afffff04ffff0bff34ff5380ffff04ffff02ff2effff04ff02ffff04ff23ff80808080ffff04ffff0bff34ff0580ff8080808080808080ffff04ff17ff8201ef808080ff8080ffff01ff088080ff018080ff0180ff018080ffff04ffff01a0dd8135d546e291df295b376aa89fc409c8c50d7f655d1ff4e845637901bc2f8fffff04ffff01ffff75ffc05168747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f636869612d6e672d6d61692f636869612d6e66742f6d61696e2f6173736574732f70696e675f72697665722e6a7067ffc07568747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f636869612d6e672d6d61692f636869612d6e66742f613231396531313434663662336234636130363733373435326638326231616139636463646365642f6173736574732f70696e675f72697665722e6a706780ffff68a0ea1f6514d221e5b8b7f0fdff7a4da8802448da111b2beed32d2975f29f362dc280ffff04ffff01a081970d352e6a39a241eaf8ca510a0e669e40d778ba612621c60a50ef6cf29c7bffff04ffff01ff02ffff01ff02ffff01ff02ffff03ff0bffff01ff02ffff03ffff09ff05ffff1dff0bffff1effff0bff0bffff02ff06ffff04ff02ffff04ff17ff8080808080808080ffff01ff02ff17ff2f80ffff01ff088080ff0180ffff01ff04ffff04ff04ffff04ff05ffff04ffff02ff06ffff04ff02ffff04ff17ff80808080ff80808080ffff02ff17ff2f808080ff0180ffff04ffff01ff32ff02ffff03ffff07ff0580ffff01ff0bffff0102ffff02ff06ffff04ff02ffff04ff09ff80808080ffff02ff06ffff04ff02ffff04ff0dff8080808080ffff01ff0bffff0101ff058080ff0180ff018080ffff04ffff01b096e1ea469479e408076f2b585b86c579c2a34cb1a47f543ad4867a8eba4e0cd30dbfee4c1b76e1e90c3ec72972a7ad7eff018080ff018080808080ff01808080",
                "solution": "0xffffa0f562d82f26b8d2e5daea583bc099ba76a32cb82a40955daca30f105bba3186e4ffa0086d05385f16156fba23b507be113a2765f40c35fcf7ee3a36121554201aa970ff0180ff01ffffff80ffff01ffff33ffa0bb3e5d7f4efa5c6c6c6696f3dd482b5c199878e6e58fdf87eaf1a3d9fe325588ff01ffffa0bb3e5d7f4efa5c6c6c6696f3dd482b5c199878e6e58fdf87eaf1a3d9fe325588808080ff8080ff01ff808080"
            }
        ]
    },
    "success": true,
    "wallet_id": 2
}
```