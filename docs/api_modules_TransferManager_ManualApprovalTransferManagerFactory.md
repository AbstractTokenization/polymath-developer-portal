---
id: modules_TransferManager_ManualApprovalTransferManagerFactory
title: ManualApprovalTransferManagerFactory
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> ManualApprovalTransferManagerFactory</h2><p class="base-contracts"><span>is</span> <a href="interfaces_IModuleFactory.html">IModuleFactory</a></p><div class="source">Source: <a href="git+https://github.com/PolymathNetwork/polymath-core/blob/v1.1.0/contracts/modules/TransferManager/ManualApprovalTransferManagerFactory.sol" target="_blank">modules/TransferManager/ManualApprovalTransferManagerFactory.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#deploy">deploy</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#">fallback</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getDescription">getDescription</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getInstructions">getInstructions</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getName">getName</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getTags">getTags</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getTitle">getTitle</a></li><li><a href="modules_TransferManager_ManualApprovalTransferManagerFactory.html#getType">getType</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="deploy" class="anchor-marker"></span><h4 class="name">deploy</h4><div class="body"><code class="signature">function <strong>deploy</strong><span>(bytes ) </span><span>external </span><span>returns  (address) </span></code><hr/><div class="description"><p>Used to launch the Module with the help of factory.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code></code> - bytes</div></dd><dt><span class="label-return">Returns:</span></dt><dd>address Contract address of the Module</dd></dl></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>(address _polyAddress, uint256 _setupCost, uint256 _usageCost, uint256 _subscriptionCost) </span><span>public </span></code><hr/><div class="description"><p>Constructor.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_polyAddress</code> - Address of the polytoken</div><div><code>_setupCost</code> - Setup cost of the module</div><div><code>_usageCost</code> - Usage cost of the module</div><div><code>_subscriptionCost</code> - Subscription cost of the module</div></dd></dl></div></div></li><li><div class="item function"><span id="getDescription" class="anchor-marker"></span><h4 class="name">getDescription</h4><div class="body"><code class="signature">function <strong>getDescription</strong><span>() </span><span>public </span><span>view </span><span>returns  (string) </span></code><hr/><div class="description"><p>Get the description of the Module.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>string</dd></dl></div></div></li><li><div class="item function"><span id="getInstructions" class="anchor-marker"></span><h4 class="name">getInstructions</h4><div class="body"><code class="signature">function <strong>getInstructions</strong><span>() </span><span>public </span><span>view </span><span>returns  (string) </span></code><hr/><div class="description"><p>Get the Instructions that helped to used the module.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>string</dd></dl></div></div></li><li><div class="item function"><span id="getName" class="anchor-marker"></span><h4 class="name">getName</h4><div class="body"><code class="signature">function <strong>getName</strong><span>() </span><span>public </span><span>view </span><span>returns  (bytes32) </span></code><hr/><div class="description"><p>Get the name of the Module.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>bytes32</dd></dl></div></div></li><li><div class="item function"><span id="getTags" class="anchor-marker"></span><h4 class="name">getTags</h4><div class="body"><code class="signature">function <strong>getTags</strong><span>() </span><span>public </span><span>view </span><span>returns  (bytes32[]) </span></code><hr/><div class="description"><p>Get the tags related to the module factory.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>bytes32[]</dd></dl></div></div></li><li><div class="item function"><span id="getTitle" class="anchor-marker"></span><h4 class="name">getTitle</h4><div class="body"><code class="signature">function <strong>getTitle</strong><span>() </span><span>public </span><span>view </span><span>returns  (string) </span></code><hr/><div class="description"><p>Get the title of the Module.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>string</dd></dl></div></div></li><li><div class="item function"><span id="getType" class="anchor-marker"></span><h4 class="name">getType</h4><div class="body"><code class="signature">function <strong>getType</strong><span>() </span><span>public </span><span>view </span><span>returns  (uint8) </span></code><hr/><div class="description"><p>Type of the Module factory.</p></div><dl><dt><span class="label-return">Returns:</span></dt><dd>uint8</dd></dl></div></div></li></ul></div></div></div>