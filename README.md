# Study-of-RSA-Attack

Hastad's Broadcast Attack

Generate public key (run first):

python generate(n,e).py gen.txt -e ... ( e is exponent )

Message encryption:

python cipher(n,e,c).py gen.txt cipher.txt -e .... -p ... ( p is your plaintext, leave here and we will attack to find it )

Attack and decode the message:

python hastad.py cipher.txt plaintext.txt


