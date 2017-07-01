# Communicating with Raspberry Pi via email
+ Send commands via email to your Raspberry Pi

# Requirements
+ Gmail account
+ Define allowed email addresses into ALLOWED = []
+ Define EMAIL address for Raspberry Pi to probe
+ Define PASSWORD for the email address password

# Process
1. Send email with empty body to the address with trigger subject to the defined email address from allowed email list
2. Wait for the reply with the key that will be attached in the subject (The key is active for 5 minutes)
3. Press reply
5. Type the command to the body of the message NOT changing the subject
6. Send the message
