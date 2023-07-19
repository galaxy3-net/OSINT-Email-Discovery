# OSINT-Email-Discovery
OSINT Email Discovery Tools

The Google Email Discovery tool uses various Google websites to discover email addresses associated with the domain.

# How is this toold useful?

- For Pen-Testers, these email addresses can be used for Phishing tests.
- Organizations often use email addresses as the user account names or some part of the email.

# Is this tool safe?

While it is always a good idea to review and vet all code and tools downloaded from the web to enaure that nothing nefarious is being done to your system or network.

I am not the author of this tool. I found it on the Internet and found it very useful as an OSINT tool. I have reviewed and vetted this OSINT script.

For additional safety with any cybersecurity related tools, I would recommend running this on a KAli Linux machine in a lab environment isolated from your home or production network.

# Downloading

Download and install the tool.

`wget https://raw.githubusercontent.com/galaxy3-net/OSINT-Email-Discovery/main/goog-mail.py`

# Running the tool

Run the tool using python2 and providing the domain to be searched.
`python2 goog-mail.py example.com`

# Demonstration

The following video is a demonstration performed in the Galaxy3 environment which is an isolated lab that I created for my students to do this type of testing.

(Video Link to be Posted Soon)