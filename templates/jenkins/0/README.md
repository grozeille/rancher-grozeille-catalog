To finish the deployment:

1. Go to the logs to get the admin password
2. Open the Master to setup the master with default plugins
3. Install the "Self-Organizing Swarm Plug-in Modules" plugin
4. Create the account/password for the slave (default: jenkins/jenkins)
5. Enable JNLP in "Configure Global Security > Agents" and set "Random"

The slave should register by itself to the master.