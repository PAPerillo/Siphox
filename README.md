# Siphox task home task

The goal of this task is to launch a tool on EC2 (or other ) to compute a DNA reverse complement using the Python [Flask](https://flask.palletsprojects.com/en/2.3.x/) based code in this repository.  The tasks required are:

1. Launch an HTTP website on port 8080 (no need to TLS).  E-mail `nick.conway@siphox.com` with the IP URL, the EC2, or other hostname URL with the functioning site.

2. Host the website using [nginx](https://www.nginx.com)


3. Make one unique feature addition the code base with documentation.

4. Create a Pull Request with your updates to this code base and including any configuration files and setup scripts used.

5. **Please send an email with your estimate for time you'll require to get the above 3 tasks complete!**

You can see an example of this running here:

http://ec2-3-144-78-5.us-east-2.compute.amazonaws.com:8080

### NOTES
This task should task about 30 minutes for someone working fast but less than 2 hours.

### TIPS and MORE NOTES

1. If using EC2, launch using an AMI such as Ubuntu 22.04 `ami-024e6efaf93d85776`
2. Make sure the security group supports the right ports
3. Don't forget your AWS PEM to ssh in
4. How are you going to get the code to AWS?
5. Take a look at `setupth.sh`
