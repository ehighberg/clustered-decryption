# Clustering-assisted Decryption
Imagine that you're an analyst at a military listening station. Every day you get hundreds of short encrypted messages from a dozen different enemy headquarters near you. The messages aren't quite long enough to decipher on their own, but you know that each enemy HQ has a single key that's unique to that command. If you could just figure out which messages came from which stations, you could put the messages together and have enough information to decrypt them. But how do you do that while the messages are still encrypted?
<br>
In this project I used NLP techniques in conjunction with unsupervised learning (clustering) to tackle the above scenario, and used the clustered (longer) messages to break their encryption keys. With 1500 messages encrypted with 150 keys, about half get clustered correctly and decrypted back into English, a better result than expected given that the decryption scheme is a simple maximum likelihood estimation.
<br>
[Presentation slides here.](https://docs.google.com/presentation/d/1HzIbVXI-uNfUXpgFEuLUU0D72augI9jaJofiqQVHXGg/edit?usp=sharing)
