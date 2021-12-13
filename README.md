# CN-PRACTICALS
# Question-1(Go Back n Sliding window protocol)
In Go back N, sender window size is N and receiver window size is always 1.
Go back N uses cumulative acknowledgements.
Go back N may use independent acknowledgements too.
Go back N does not accept the corrupted frames and silently discards them.
Go back N does not accept out of order frames and silently discards them.
Go back N leads to retransmission of entire window if for any frame, no ACK is received by the sender.

![output1(1)](https://user-images.githubusercontent.com/77627369/145757497-b5d321c4-6146-4d52-8762-fbbd697b9b23.png)
![output1(2)](https://user-images.githubusercontent.com/77627369/145757504-0b78b980-32dc-45f5-b85b-24f8da15c5e3.png)
![output1(3)](https://user-images.githubusercontent.com/77627369/145757510-bef4462b-4060-4154-882e-f2a8dd960288.png)
# Question-2(Cyclic Redundancy Check[CRC] error detection algorithm for noisy channel)
A cyclic redundancy check (CRC) is an error-detection code that is extensively used in digital networks and storage devices to detect unintentional data changes. A short check value is applied to blocks of data entering these systems, based on the remainder of a polynomial division of their contents.
The calculation is performed upon retrieval, and if the check values do not match, corrective action against data corruption can be done.
The algorithm is based on cyclic codes, and the check (data verification) value is a redundancy (it increases the message without adding information). CRCs are popular because they are straightforward to construct in binary hardware, mathematically evaluate, and are particularly good at identifying typical errors caused by noise in transmission channels.The function that generates the check value is sometimes employed as a hash function because it has a defined length.
