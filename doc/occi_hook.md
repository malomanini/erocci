

# Module occi_hook #
* [Description](#description)
* [Function Index](#index)
* [Function Details](#functions)

.

Copyright (c) (C) 2013, Jean Parpaillon

This file is provided to you under the Apache License,
Version 2.0 (the "License"); you may not use this file
except in compliance with the License.  You may obtain
a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.

__Authors:__ Jean Parpaillon ([`jean.parpaillon@free.fr`](mailto:jean.parpaillon@free.fr)).

<a name="index"></a>

## Function Index ##


<table width="100%" border="1" cellspacing="0" cellpadding="2" summary="function index"><tr><td valign="top"><a href="#loop-0">loop/0</a></td><td></td></tr><tr><td valign="top"><a href="#register-1">register/1</a></td><td></td></tr><tr><td valign="top"><a href="#start_link-0">start_link/0</a></td><td></td></tr><tr><td valign="top"><a href="#trigger-2">trigger/2</a></td><td></td></tr></table>


<a name="functions"></a>

## Function Details ##

<a name="loop-0"></a>

### loop/0 ###

`loop() -> any()`

<a name="register-1"></a>

### register/1 ###

<pre><code>
register(X1::<a href="#type-hook_type">hook_type()</a>) -&gt; ok | {error, term()}
</code></pre>
<br />

<a name="start_link-0"></a>

### start_link/0 ###

<pre><code>
start_link() -&gt; ok
</code></pre>
<br />

<a name="trigger-2"></a>

### trigger/2 ###

<pre><code>
trigger(Occi_node::<a href="#type-occi_node">occi_node()</a>, Occi_action::<a href="#type-occi_action">occi_action()</a>) -&gt; {true, <a href="#type-occi_node">occi_node()</a>} | false | {error, term()}
</code></pre>
<br />

