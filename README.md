
Ejecuta el archivo main y sigue las instrucciones en pantalla.

```mermaid
classDiagram
characters_properties o-- characters_stats
characters_properties o-- characters_births
characters_properties : int ID/Primary Key
characters_properties : String Name
characters_properties : String Element
characters_properties : int Rarity
characters_properties : String Weapon
characters_properties : String Class
characters_stats : int ID/Primary Key
characters_stats : int HP
characters_stats : int ATK
characters_stats : int DEF
characters_stats : String Food
characters_births : int ID/Primary Key
characters_births : Date Birthdate
characters_births : String Region
characters_births : String Constellation
