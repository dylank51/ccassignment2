Dylan Kirby - C15523157
IP:Port: 146.148.13.84:5000
Git-repo: https://github.com/koybz/ccassignment2

Sorry, I did not have time to make a video instead I have provided screenshots for part 1 and 2 instead

For Part 1:

1. On manager run: 'docker swarm init'	 
On the workers run: 'docker swarm join --token' followed by the token supplied by the manager
	
2. app.py file is in the github, when running it can be tested using testing
  
  image to show part 1: https://imgur.com/a/xUKX4
	
For Part 2:
	
1. On the manager run: 'docker service create --replicas 5 -p 80:80 --name web nginx'

	

     
     
 
