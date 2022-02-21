# DuckDigitalID

This is a basic outline with proof of concept of using the minting process on Cardano Blockchain to create a multi-use digital ID. 

The basic Idea is to create one time-locked minting script used to create an ID system that can be used for TX validation and account management. 
I propose creating one policyID and name(in hexadecimal form) as a unique identifier for each user/account.
The unique identifier could be an account number or it could be a user-name. For the sake of simplicity, I have chosen to use AliceDuckID and BobDuckID as the name, both minted under the same policy number, and timed locked to prevent replication. 

# Use Case

The DuckID can be used as an input in a script, releasing funds to specific users. 

The DuckID can be used to assign roles in a DAO/Server. 

The DuckID can be used to establish trusted users in a public space by requiring members to have a policy key minted with their unique identifier. 

The DuckID can be used as a voting tool, requiring each participant to possess a valid personalized ID with the policy number tied to a corresponding election.

Alice's Idetification:
https://pool.pm/b98829dd255068cb3d742aebb6eb333fbbb8111763d4c8a750f2b708.416c6963654475636b4964

Bob's Identification:
https://pool.pm/b98829dd255068cb3d742aebb6eb333fbbb8111763d4c8a750f2b708.426f624475636b4964

Generic Template:
https://pool.pm/b98829dd255068cb3d742aebb6eb333fbbb8111763d4c8a750f2b708.4475636b4964
