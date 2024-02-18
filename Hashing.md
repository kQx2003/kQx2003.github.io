What is hashing?
Hashing is the process of transforming any given key or a string of characters into another value. This is usually represented by a shorter, fixed-length value or key that represents and makes it easier to find or employ the original string.

The most popular use for hashing is the implementation of hash tables. A hash table stores key and value pairs in a list that is accessible through its index. Because key and value pairs are unlimited, the hash function will map the keys to the table size. A hash value then becomes the index for a specific element.

A hash function generates new values according to a mathematical hashing algorithm, known as a hash value or simply a hash. To prevent the conversion of hash back into the original key, a good hash always uses a one-way hashing algorithm.

Hashing is relevant to -- but not limited to -- data indexing and retrieval, digital signatures, cybersecurity and cryptography. 

What is hashing used for?
Data retrieval
Hashing uses functions or algorithms to map object data to a representative integer value. A hash can then be used to narrow down searches when locating these items on that object data map.

For example, in hash tables, developers store data -- perhaps a customer record -- in the form of key and value pairs. The key helps identify the data and operates as an input to the hashing function, while the hash code or the integer is then mapped to a fixed size.

Hash tables support functions that include the following:

insert (key, value)
get (key)
delete (key)

<img src="https://cdn.ttgtmedia.com/rms/onlineimages/sqlserver-hash_table_example-f.png">

Digital signatures
In addition to enabling rapid data retrieval, hashing helps encrypt and decrypt digital signatures used to authenticate message senders and receivers. In this scenario, a hash function transforms the digital signature before both the hashed value (known as a message digest) and the signature are sent in separate transmissions to the receiver.

Upon receipt, the same hash function derives the message digest from the signature, which is then compared with the transmitted message digest to ensure both are the same. In a one-way hashing operation, the hash function indexes the original value or key and enables access to data associated with a specific value or key that is retrieved.

<img src="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f.png">
