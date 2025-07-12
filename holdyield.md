---
layout: default
title: HoldYield - Wikimint (WMT)
description: Wikimint (WMT) is a BEP-20 token built on BSC to power content creators and communities. Earn rewards by writing, engaging, and staking. Claim your free airdrop now.
date: 2024-12-18
noindex: true
---

  <div class="container py-5 text-center">
    <h1 class="mb-4">🚀 Wikimint HoldDrop</h1>
    <p>Hold at least <strong>1 WMT</strong> in your wallet and claim <strong>0.0001 USDT</strong> to your FaucetPay every 30 seconds!</p>
    <button id="connectWalletBtn" class="btn btn-primary my-3">Connect Wallet</button>
    <div id="holderUI" style="display:none;">
      <div id="claimForm" class="mt-4">
        <input type="text" id="faucetpayAddress" class="form-control mb-2" placeholder="Enter your FaucetPay USDT address">
        <button id="claimBtn" class="btn btn-success">Claim Reward</button>
      </div>
      <div id="countdown" class="text-danger fw-bold mt-3" style="display:none;"></div>
    </div>
    <div id="status" class="mt-4"></div>
  </div>
  

<script src="/wmt/assets/lib/web3.min.js"></script>
<script src="/wmt/assets/js/hold.js"></script>
<script src="/wmt/assets/js/script.js"></script>