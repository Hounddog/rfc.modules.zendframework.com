### RFC Status: Work-in-Progress

<!--
RFC Statuses:
* Work-in-Progress - RFC is still being worked on by the RFC Author
* Open for Comments
* Voting
* Accepted
* Declined
-->

RFC Author(s): [Martin Shwalbe](https://github.com/Hounddog), [Pierre-Emmanuel Manteau](https://github.com/PEM-FR)

## Abstract
<h3>Proposal for ZendFramework 2 Module Evalutaion</h3>
<h4>Why should we evaluate modules?</h4>
<ul>
<li>When you are looking for a module, you might want to know abotu the quality of the module, and not choose randomly.</li>
<li>If we ever reach a point where we have thousands of modules, and several of them doing the same thing, you might want to be able to compare them.</li>
<li>As a module provider, we want to ensure a certain level of quality in the module provided, or at least information about this quality to be judged by users. It is necessary to be deemed reliable.</li>
</ul>

<h4>How to evaluate them properly?</h4>
<ul>
 <li>Evaluating ones code is not always an easy task and might be very subjective at times depending on the one evaluating.</li>
 <li>We need to rely on a set of informations, among them :
<ul>
 <li>reactivity (speed of issue resolving, speed of PR treatment).</li>
 <li>user ratings (documentation, ease of installation, quality of support, module is working as expected), with 4 stars, one for each, or something like that.</li>
 <li>nb of downloads. (int)</li>
 <li>are there any unit tests? (yes / no)</li>
 <li>is there any documentation? (yes / no)</li>
 <li>nb of open/closed issues</li>
 <li>nb of waiting/merged Pull Requests</li>
 <li>...</li>
</ul>
</li></ul>

<h4>Statistics and filters over global rankings</h4>
<ul>
<li>We consider that it is not our role to compile all these information into one note, as some factors may be wrongly influenced. For example, is a stable module with no update for 6 months better than an "unstable" module with a lot of issues and PR, but which solves both at a fast pace?
We believe it is up to the final user to make the decision what he/she deems better for his/her context.</li>
<li>Providing a set of informations that helps a user decide seems to be a better option than a global blackbox ranking.</li>
<li>In order to allow users to search by their own criteria, own order of importance, we will provide filters and indexes on information subsets.</li>
</ul>

<h4>What is a module, what information shall it provide?</h4>
<ul>
<li>It MUST have a module.php file in the root folder</li>
<li>It MUST have a licence.md</li>
<li>It MUST have a readme.md</li>
<li>It can provide additional information in the readme.md such as :
<ul>
<li>@zf-version : 2.x</li>
<li>...</li>
</ul></li>
</ul>

<!-- In the abstract, explain in a brief paragraph what problem(s) this module solves. Be sure to include a good description of the use-cases where this module would be useful, and what value it offers to those who use it. -->

## Proposed Features

<h4>User GitHub Login</h4>
<h4>User account management</h4>
<h4>Module submission</h4>
<ul>
    <li>Display list of user owned repositories/collaborator repositories</li>
    <li>Dependencies: Module.php, README(*), LICENCE(*)</li>
</ul>
<h4>Proposal for statistics</h4>

<!-- Provide a list of features that you think should be included in the module's initial release. Also explain what parts of the module should be extensible via third-party modules. -->

## Example(s)

You can see a running(?) example here : http://zf-modules.bigbrowser.net
<!-- If possible, provide code samples which illustrate end-user usage of the proposed module. -->