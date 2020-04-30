# glpi-chatbot
API integration from Vizir to GLPI to build chatbots that create tickets, check ticket status,...

GLPI is therefore a tool for managing computer tickets (incidents, service requests, etc. ...) which has the distinction of being open source!

Published by Teclib Group, a French company that puts responsible innovation at the heart of its values, GLPI has become one of the challengers of the ITSM market in a few years, facing mastondons such as ServiceNow, EasyVista or Jira Service Desk of Atlassian. Indeed, these two aspects (open source and French) have enabled him to establish himself in companies such as La Poste, Airbus, Vinci, Bolloré and La Redoute but also in prestigious public bodies such as the Conseil d'Etat, Inria, the University of Paris 1 Panthéon la Sorbonne and the National Police.

Despite its videos a little old school (as you may have noticed above), GLPI's functionalities have nothing to envy to its peers: ITIL v2 compatible service center (bravo), asset management, quality control, software inventory and license management, knowledge base and FAQ online, statistics and reports in real time, etc... This tool allows you all your IT processes, however complex they may be.

If you wish to switch your MTSI to GLPI, several options are available to you. If you're an ISD Ninja Warrior who doesn't mess with data security, you'll probably opt for the Open Source option to install on your servers on your own. If you have no time to waste and are looking for maximum efficiency, you will probably opt for the Cloud all inclusive option. These choices are perfectly summarized in a nutshell on the tool's home page. All you have to do now is decide!

# Integrations
If you have (or will) opt for GLPI, it is because you want to streamline your IT processes internally. And you're to be congratulated for it.

If you are precisely on this page, it is because you are curious about the interest of setting up a chatbot to digitize or fluidify your computer support. Your ITSM tool allows you to better manage requests, reduce processing time and improve tracking. But it does not reduce the number of tickets processed (it may even increase the number of tickets processed) nor does it offer real-time and continuous support.

Create and interface a chatbot to GLPI will allow you to deal with these last two points.
Here are some ideas of how you could interface a chatbot with GLPI:

- Qualification of incidents and distribution of the incident to the right team according to subject and urgency
- To carry out research in the documentary base GLPI directly since the chatbot hosted on Teams or on Hangout (or any other support)
- Distill standalone level 0 or level 1 resolution procedures to limit the number of tickets created
- Facilitate the creation of tickets by making it available from your employees' favourite instant messaging tool: avoids hacker solicitation by email / phone / physical mail

# API actions
## POST :
- Report and qualify an incident in GLPI from a natural language conversation
- Trigger a request for device from the chatbot via GLPI
## GET
- Consult my tickets / current requests
- Relaunch late tickets / requests
- Search for information in the GLPI knowledge base
