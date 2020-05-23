## Configuration Management ##

To run the playbook locally in your machine:
* Add the public ssh key to the host
* Add the public ssh key to github repository
* Know the bot token and bot signing secrete
* Run the command below:

        ansible-playbook -i \path\to\inventory.txt \Path\to\bot-playbook.yml --extra-vars "secret1=<BOT TOKEN> secret2=<BOT SIGNING SECRET>"
