## Token ~~Factory~~ Sweatshop

This token sweatshop allows easy creation of a standard ERC20 token on the Ethereum blockchain for less. Its GasPrice is locked to 1 Gwei.

I forked this repository because Mist's oracles for gas prices on contracts are far too rigid and for someone who's not in a hurry to put up a token, a gas price of 20 Gwei is overkill.

Of course, if the SafeLow on https://ethgasstation.info is >5 Gwei, expect a transaction through this to take forever. That's when you'll be much better off deploying for 20 Gwei on the original Token Factory at https://tokenfactory.surge.sh

Just like the original recipe, this dApp requires an injected web3 (Mist or Metamask) to function. It also has uPort support. It does not use an on-chain factory at this point in time.

## Hey Daniel, stop being an idiot and install Metamask...

Metamask is a brilliant software that injects a web3 stim pack into your boring old browser but its lack of support for hardware wallets and the upcoming end of the road for the Chrome App Store isn't convincing.

Plus, hardware wallets exist for a reason, thus using Mist to have hardware wallets sign transactions enables us to deploy contracts to the blockchain that are controlled and can only be controlled by the private key that never leaves the wallet. However, not everyone wants to deal with the 20 Gwei GasPrice. I cetrainly don't.

## ...then why don't you download Parity instead?

Parity's warp sync has issues. It's probably something personal against me. I dunno lol.

**This code is licensed under MIT.**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
