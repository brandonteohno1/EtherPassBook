<h1>Analysis and Design Brainstorming Nodes</h1>
<bR><br>
<b>27-Mar-2018:</b>
<ol>
<li>Run Ethereum client at a PC for a private blockchain, this will serve as the first node or server.</li>
<li>Create an app to read and write the data.</li>
<li>Run Ethereum client at another PC for subsequent node, this will serve as fail-over and redundancy.</li>
</ol><Br>
<b>1-Apr-2018:</b>
<Br>
<ol>
<li>User acquires a server (preferably in the cloud) as first node.</li>
<li>Setup the first node under consortium network.</li>
<li>Create multiple accounts under the node : each login user will have one account.</li>
<li>Each account has a contract as extension (program and database).</li>
<li>Users will invoke contracts to retrieve the password.</li>
<li>If the Ether balance field of each account is a string type, it can be used to store other data asides from Ether balance.</li>
<li>User should setup another node as backup.</li>
</ol><Br>
<b>2-Apr-2018:</b>
<Br><ol>
<li>Audit trail data will be stored as blockchain's transaction.</li>
<li>New account must be nominated by an existing account.<br>
So that the password database (key/value pairs) can be cloned from nominator to the nominee's contract.
</li>
<li>The contract can be programmed to set access rules for the password entries - i.e certain passwords can only be retrieved by certain people.
</ol>