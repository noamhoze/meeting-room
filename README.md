## Steps for starting the app ##
 * Run 'python main.py'
 * Running 'ngrok http 5000'
 * Inserting the https url (gotten from the step above) to the configuration of our skill at https://developer.amazon.com.
 
## Examples of changing the DB ##
 * import json, socket
 * s = socket.socket()
 * s.connect(("127.0.0.1", 9999))
 * s.send(json.dumps({"name": "yellow", "number_of_people": 0, "max_people": 10}).encode('UTF-8'))
