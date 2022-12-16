## Instructions to use the bullethell engine.

1st: Install URP (Universal rendering pipeline), this is optional HOWEVER you would need to comment out ALL recolouring logic and replace all sprite materials.

2nd: Make sure the gun objects have a "gun" tag

3rd: Create a pool manager (you can use your game manager for this) and give it the "pool manager" script, then type the name of the pool manager into every bossAI instance

4th: Make sure your player has a tag named "Player" (case-sensetive)

5th: You need to add your own damage taking logic, most of this is done for you by the "Damage player" script, this is to allow customizability

6th: Make sure ALL fields are filled in for the attack configs, they are not filled. You will get errors.
