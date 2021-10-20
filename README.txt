To run the project you should install Unreal Engine 4. 
https://www.unrealengine.com/en-US/download?install=true
Using it open fps.uproject file. Also use it to build the project.

Link to bulided project:
https://drive.google.com/drive/folders/1O0pHy75kYDpZ54Px6pJ2S5Aey5skIsiE?usp=sharing


This is a module system for AI Behavior, which you can use for making your own games.

Behavior provides 8 different states: Idle, Explore, Follow, Melee Attack, Shoot Attack, Hiding, Retreat, Heal. 
 
Quick start:
1. Run the project
2. Open folder "AI"
3. Copy the folder "AI" to your project folder
4. Choose necessary behavior scripts
5. Test and integrate


States:
1. Idle-Explore state runs when enemy can not see player and has high health level.
2. Follow state runs when enemy can see player and player if too far to attack.
3. MeleeAttack state runs when enemy is close to player.
4. ShootAttack state runs when enemy is enough far from player to shoot.
5. Heal: runs when enemy has low health level and see aid first kit.
6. Cover: runs when enemy is going to shoot and see cover.
7. OutOfCover: runs when enemy is in cover and does not see player.
8. Retreat: runs when enemy has low health level and does not see aid first kit.
9. AnyState — special state. If conditions for Retreat state are true, enemy switches to the state Retreat from any other (except Heal).
