# 5D-Cistercian-Lattice-Challenge-Response-Protocol
5D Cistercian Lattice Challenge-Response Protocol

This modified code implements a challenge-response protocol using the 5D Cistercian lattice and custom encryption. Here's how it works:

1. A challenge string is generated, which in this case is set as "Hello, world!".
2. The adaptive complexity of the challenge is calculated based on the length of the string.
3. An encryption key is generated from the adaptive complexity.
4. The challenge string is encrypted using the 5D Cistercian lattice and custom encryption with the generated encryption key.
5. The encrypted challenge is displayed to the user.
6. The user is prompted to enter a response.
7. The user's response is encrypted using the same encryption key and encryption algorithm.
8. The encrypted response is then decrypted using the same encryption key and algorithm.
9. The decrypted response is compared to the original challenge.
10. If the decrypted response matches the challenge, it means the user has successfully completed the challenge-response protocol. Otherwise, the challenge is considered failed.

You can run this code and test the challenge-response protocol by entering the response string when prompted. The code will compare the decrypted response with the original challenge and display whether the challenge passed or failed.
