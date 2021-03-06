---
layout: post
title: Keyshanc Ported to Javascript
tags: keyshanc, javascript
description: Keyshanc has been ported to Javascript to enable decryption of Keyshanc on websites. A demo is provided.
keywords: keyshanc, keyboard encrypter, keyboard encryption, javascript
hashtag: keyshanc
---
This post demonstrates how to use the <a href="https://github.com/Networc/keyshanc/tree/master/javascript">Keyshanc Javascript</a>. Type your Keyshanc password in the password field and press the "Keyshanc" button. If you want to disable Keyshanc, delete all text from the password field and press the "Keyshanc" button again.<br />
<h3>Examples</h3>
Use "aragorn" as the Keyshanc password and paste the following into the "Input" text box:<br />
<pre><code>&amp;TxJYUT$J1}JFKUT$J18xDJmqqJmT(JUTJ18xJ(mK/TxzzJFUT(J18xD</code></pre><br />
Use "bilbo" as the Keyshanc password and paste the following into the "Input" text box:<br />
<pre><code>7Ao!4KA'!&lt;E!zdKA'!&lt;Roa!P55!PA^!KA!&lt;Ro!^PdpAoVV!zKA^!&lt;Roa</code></pre><br />
<br />

Keyshanc Password:<br />
<input type="password" id="password" /><input type="button" value="Keyshanc" onclick="keyshanc(document.getElementById('password').value)" /><br />
Input:<br />
<textarea rows="4" cols="60" id="inText" onkeypress="decryptKeyshanc()"></textarea><br />
Output:<br />
<textarea rows="4" cols="60" id="outText"></textarea><br />
<br />

This entire post is MIT Licensed.
