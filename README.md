# RE-Framework-for-Linear-Process

<ol>
<li>It is very much help for those who are looking to use the RE Framework for a Linear Process.</li>
<li>This workflow will run for only One time if the transaction item is processed without any System exceptions. </li>
<li>If any System exceptions occurs then default retry mehanism will be followed.</li>
<li>If any Business Rule Exception is provided then the control will be stopped without any retry mechanism.</li>
<li>If you required to retry the process even though any BE occurs, we have to customise the State machine.</li>
<ol>
