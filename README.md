# RbxLib | Python 3.8.6
Python library for the Roblox API, built simple for simple projects.
I built this so I could have a basic library to get information from the Roblox API for a Discord Bot.  After finding out there are no good libraries I made this for other devs who may need this.  I hope it's helpful for you.  Open an issue for any bug reports or DM me on discord @ Elmo#2963, or visit my main (Discord)[discord.gg/tfRNz4xNSP] I will have a support channel made in it where you can send your questions.

Final message, thank you for choosing to use my library.


# Documentation

<details>
  <summary>Full List of Functions</summary>
  
  1. doesUserExist()
  2. getUserId()
  3. getUserName()
  4. getDisplayName()
  5. getUserProfile()

</details>

--- 

## Importing
`import rbxlib as rbx`

This will import the entire library and all it's functions.


--- 
## Functions

### doesUserExist()
<details>
  <summary>Expand for more...</summary>

  Arguments: user[String/Integer]

  Example:

  ```python
  print(rbx.doesUserExist("TheROBLOXMAPMAKE")) -> True
  print(rbx.doesUserExist(378776480)) -> True
  ```

  Notes: This function will return `True` or `False` depending on if the user exists or not.
</details>

--- 

### getUserId()
<details>
  <summary>Expand for more...</summary>

  Arguments: name[String]

  Example:

  ```python
  print(rbx.getUserId("TheROBLOXMAPMAKE")) -> [True, 378776480]
  print(rbx.getUserId("OAIWhofnahi")) -> [False, 'User not found']
  ```

  Notes: You will input a username and it will return an array, the first index is either `True` or `False`, the second index will be the `userId` or the error message.
</details>

--- 

### getUserName()
<details>
  <summary>Expand for more...</summary>

  Arguments: id[Integer]

  Example:

  ```python
  print(rbx.getUserName(378776480)) -> [True, 'TheROBLOXMAPMAKE']
  print(rbx.getUserId(32897428937589)) -> [False, 'The user id is invalid.']
  ```

  Notes: You will input a userId and it will return an array, the first index is either `True` or `False`; The second index will be the `username` or the error message.
</details>

--- 

### getDisplayName()
<details>
  <summary>Expand for more...</summary>

  Arguments: id[Integer]

  Example:

 ```python
  print(rbx.getDisplayName(378776480)) -> [True, 'TheROBLOXMAPMAKE']
  print(rbx.getDisplayName(32897428937589)) -> [False, 'The user id is invalid.']
 ```

  Notes: You will input a userId and it will return an array, the first index is either `True` or `False`; The second index will be the `displayname` or the error message.
</details>

--- 

### getUserProfile()
<details>
  <summary>Expand for more...</summary>

  Arguments: user[String/Integer]

  Example:

 ```python
  print(rbx.getDisplayName(378776480)) -> [True, 'TheROBLOXMAPMAKE']
  print(rbx.getDisplayName(32897428937589)) -> [False, 'The user id is invalid.']
 ```

  Notes: You will input a userId and it will return an array, the first index is either `True` or `False`; The second index will be the `displayname` or the error message.
</details>
