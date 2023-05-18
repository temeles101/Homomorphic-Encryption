# Homomorphic encryption

  I participated in the Research Experience for High Schooler program (REHS) through the University of Notre Dame. With the assistance of Professor Taeho Jung, I learned about Homomorphic encryption, and this project is the result of my research. 

  The programs are run simulatenously, where the client(client.py) encrypts and serializes data before sending it to the server(server.py). The server deserializes the encrypted data received and enters it into a linear regression equation. Then the server sends the result of the linear regression equation back to the client in serialized form. The client recives the data, deserializes and decrypts it, and then the client reads the data or the solution. The purpose of these programs are to demonstrate how Homomorphic encryption protects the information of the client while also enabling the server to work with the client's personal information in encrypted form, thus providing a more secure approach to providing and recieving personal information. 

