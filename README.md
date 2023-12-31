<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Setup</h1>
This is to help you setup osTicket to be used by your organization. It's in the system. It's up and running. Now people just need to be able to use it.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine/Computer)
- Remote Desktop
- Internet Information Services

<h2>Operating Systems Used</h2>

- Windows 10

<h2>List of Prerequisites</h2>

- osTicket Successfully installed.
- Administrative access to osTicket

<h2>Things to Do</h2>

- Create a role
- Create a department
- Create a team
- Determine who can create a ticket
- Create new agent accounts
- Create new user accounts
- Create and change SLA plans
- Create help topics

<h2>Important to Note</h2>

In osTicket, when doing difference things, you will either need to be in the Admin Panel or Agent Panel. An easy way to tell which panel you're in is by looking in the top right of the screen.

If you see this:
<p>
<a href="https://imgur.com/ydgyH6q"><img src="https://i.imgur.com/ydgyH6q.png" title="source: imgur.com" /></a>
</p>
This mean you're already in the ADMIN panel and clicking that link will SEND YOU to the AGENT panel.

If you see this:
<p>
<a href="https://imgur.com/sXapVmR"><img src="https://i.imgur.com/sXapVmR.png" title="source: imgur.com" /></a>
</p>
Then You're in the AGENT panel and clicking this link will SEND YOU to the ADMIN panel.

To help, I try to emphasize whether I'm talking about the Agent *PANEL*, Agents *TAB*, or Agents *SECTION*.
<br/>



<h3>Create a role</h3>
<p>
<a href="https://imgur.com/lbjfF8M"><img src="https://i.imgur.com/lbjfF8M.png" title="source: imgur.com" /></a>
</p>
<p>
Roles are for designating a title and a set of priveleges necessary for whoever needs to do whatever. In other words, a person in a specific Role has all the abilities deemed necessary for that Role.
</p>
<p>
While in the Admin Panel, you can create new roles by selecting the Agents *TAB*, selecting the Roles section, and clicking the Add New Role button. First, you name your role. Then, you decide what it has the ability to do. It may be best, if starting from scratch, to create a role for your account that can do absolutely everything.
</p>
<br />

<h3>Create a department</h3>
<p>
<a href="https://imgur.com/PIN4H3i"><img src="https://i.imgur.com/PIN4H3i.png" title="source: imgur.com" /></a>
</p>
<p>
Departments are used to make sure tickets of a specific variety can be sent to the department responsible for satisfying that ticket's conditions.
</p>
<p>
While in the Admin panel, you can create new departments by selecting the Agents *TAB*, selecting the Departments section, and clicking the Add New Department button. In this space, you can name your department, set it's status, determine Service Level Agreements (SLAs), and much more.
</p>
<br />

<h3>Create a team</h3>
<p>
<a href="https://imgur.com/U3RJtqP"><img src="https://i.imgur.com/U3RJtqP.png" title="source: imgur.com" /></a>
</p>
<p>
Teams are for smaller groups within a department that only apply to certain agents within that department. For example, there may be many members in the IT department, but only a select few are chosen to be System Admins or Level III support.
</p>
<p>
To create a Team, while in the admin panel, select the Agents *TAB*, the Teams section and click the Add New Team button. In here, you can designate a name for the team, the team lead, and the agents that you choose for that specific team.
</p>
<br />

<h3>Determine who can create a ticket</h3>
<p>
<a href="https://imgur.com/fM8pgNt"><img src="https://i.imgur.com/fM8pgNt.png" title="source: imgur.com" /></a>
</p>
<p>
In the Admin Panel, select the Users section under the Settings tab. Here you can set things like Name formatting and if registration is required, among other things like account lockout policy. Be sure to save your changes!
</p>
<br />

<h3>Create new agent accounts</h3>
<p>
<a href="https://imgur.com/nEre4hc"><img src="https://i.imgur.com/nEre4hc.png" title="source: imgur.com" /></a>
</p>
<p>
Agents are the people who answer the tickets and fix the issues plaguing your organization.
</p>
<p>
In the Admin panel, select the Agents *TAB*, the Agents *SECTION*, and click the Add New Agent button. Here, you enter your new agent's contact information, establish login information, what department the belong to, what role within that department, what abilities they have, and any teams they may be a part of.
</p>
<br />

<h3>Create new user accounts</h3>
<p>
<a href="https://imgur.com/Zl9yWuG"><img src="https://i.imgur.com/Zl9yWuG.png" title="source: imgur.com" /></a>
</p>
<p>
User are the people in the organization who, essentially, have the problems and create the tickets.
</p>
<p>
To create a new user, in the Agent *PANEL*, select the Users section and click the Add User button. Here, you can enter their contact info and you're done.
</p>
<br />

<h3>Create and change SLA plans</h3>
<p>
<a href="https://imgur.com/IAeL4pu"><img src="https://i.imgur.com/IAeL4pu.png" title="source: imgur.com" /></a>
</p>
<p>
Service Level Agreements (SLAs) are basically how you would classify a ticket based on importance and how fast it needs to be resolved.
</p>
<p>
In the Admin panel, select the SLA section under the Manage tab and click the Add New SLA Plan button. Here, you can name your SLAs, determine your grace period (the time in which it needs to be resolved), and the schedule it falls under. Some tickets can fall under and SLA that, at some point, can be resolved on business days. Others may need to be resolved as soon as possible and have a stricter SLA with a smaller grace period and is active 24/7.
</p>
<br />

<h3>Create help topics</h3>
<p>
<a href="https://imgur.com/e2K5d5g"><img src="https://i.imgur.com/e2K5d5g.png" title="source: imgur.com" /></a>
</p>
<p>
Help Topics are a good resource to use if there is a common problem or to establish some groud rules and criteria for things like SLA classification.
</p>
<p>
In the Admin panel, select the Help Topics section under the Manage tab and click the Add New Help Topic button. Here you can name your topic and type in whatever information you feel is necessary to address the stated topic.
</p>
<br />

<h3>Done</h3>
<p>
That should be enough to get started with osTicket.
</p>
<br />
