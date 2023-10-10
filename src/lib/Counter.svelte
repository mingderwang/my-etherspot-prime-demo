<script>
    import {Button, Heading} from "@kahi-ui/framework";
    //import { PrimeSdk } from '@etherspot/prime-sdk';
    let clicks = 0;
    function on_click(event) {
        clicks++;
   //     const primeSdk = new PrimeSdk({ privateKey: process.env.VITE_WALLET_PRIVATE_KEY }, { chainId: 80001, projectKey: '' })
  //  primeSdk.getCounterFactualAddress().then(console.log)
    }
</script>

<Heading>
    Clicks: {clicks}
</Heading>

<Button on:click={on_click}>Add +1</Button>