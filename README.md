# RbxLib
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

## Importing
`import rblxlib as rbx`

This will import the entire library and all it's functions.


### doesUserExist(user) | Function
<details>
  <summary>Expand for more...</summary>
  Arguments: user[String/Int]
  Example:
  ```python
  print(doesUserExist("TheROBLOXMAPMAKE")) -> True
  print(doesUserExist(378776480)) -> True
  ```
  Notes: This function will return `True` or `False` depending on if the user exists or not.
</details>




