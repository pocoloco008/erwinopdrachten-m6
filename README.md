# erwinopdrachten m6

opdracht 1

https://github.com/pocoloco008/erwinopdrachten-m6/tree/main/My%20project%20(1)/Assets/scripts


opdracht 2

classDiagram

class Tower {
    +cost : int
    +range : float
    +fireRate : float
    +damage : int
    +UpgradeTower()
}

class UpgradeUI {
    +Show()
    +Hide()
    +SetTarget(Tower)
}

class UpgradeButton {
    +OnClick()
}

class CloseButton {
    +OnClick()
}

class Enemy {
    +currentHealth : int
    +TakeDamage()
}

class EnemyHealthBar {
    +UpdateHealth()
}

Tower --> UpgradeUI : opent
UpgradeUI --> UpgradeButton
UpgradeUI --> CloseButton
Tower --> Enemy : valt aan
Enemy --> EnemyHealthBar : gebruikt



opdracht 3

https://github.com/pocoloco008/erwinopdrachten-m6/tree/main/My%20project%20(1)/Assets/scripts
https://github.com/pocoloco008/erwinopdrachten-m6/blob/main/My%20project%20(1)/Assets/scripts/inventory.cs



opdracht 4


<img width="800" height="409" alt="image" src="https://github.com/user-attachments/assets/9422d5e8-5624-4fdb-91d8-6eed147015ac" />
