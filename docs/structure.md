##### Сцены

###### Platformer Demo:

Платформер-сегмент, есть пропасти, летающие платформы, в конце уровня глубокая яма из которой нельзя выбраться.



##### Объекты

Тайлмап, низкая трава, высокая трава, игрок, 3х-слойный фон деревьев, камера, дирлайт за текстурами.

Префабы: Модель персонажа, 3х-слойный фон деревьев, трава.



##### Игрок



###### Transform

* Position
* Rotation
* Scale



###### Sprite Renderer

* Sprite
* Color
* Flip
* Draw Mode
* Mask Interaction
* Sprite Sort Point
* Material
* Sorting Layer
* Order in Layer



###### Animator

* Controller
* Avatar
* Apply Root Motion
* Animate Physics
* Update Mode
* Culling Mode



###### Rigidbody 2D

* Body Type
* Material
* Simulated
* Use Auto Mass
* Mass
* Linear Damping
* Angular Damping
* Gravity Scale
* Collision Detection
* Sleeping Mode
* Interpolate
* Freeze Position
* Freeze Rotation
* Include Layers
* Exclude Layers



###### Capsule Collider 2D

* Material
* Is Trigger
* Used By Effector
* Composite Operation
* Offset
* Size
* Direction
* Layer Override Priority
* Include Layers
* Exclude Layers
* Force Send Layers
* Force Receive Layers
* Contact Capture Layers
* Callback Layers



###### Player Character (Script)

* Player\_id
* Max\_hp
* Invulnerable
* Move\_accel
* Move\_deccel
* Move\_max
* Can\_jump
* Double\_jump
* Jump\_strength
* Jump\_time\_min
* Jump\_time\_max
* Jump\_gravity
* Jump\_fall\_gravity
* Jump\_move\_percent
* Ground\_layer
* Ground\_raycast\_dist
* Can\_crouch
* Crouch\_coll\_percent
* Reset\_when\_fall
* Fall\_pos\_y
* Fall\_damage\_percent



###### Character Anim (Script)



###### Character Hold Item (Script)

* Hand







##### Скрипты

Carry Item - Скрипт позволяющий объекту переноситься.

Character Anim - Добавляет анимации игроку.

Character Hold Item - Возможность нести/подбирать предметы.

Follow Camera - Отвечает за движение камеры за игроком.

Lever - Отвечает за механику рычага.

Player Character - Управление персонажем.

Character Controls - Назначение клавиш.

The Audio - Звук.

