
INSERT INTO characters (name,age,hp,gender,style,mana,class,race,xp,`level`,height) 
VALUES
	('Jacinto',12309,999,'F','R',100000,'Mg','Sg',1000000,0,2.1),
	('Alejandro',2,0,'M','M',1,'De','Nd',100,2,1.2),
	('Paca',43,100,'F','G',0,'Wa','Lo',500,70,4.52),
	('Maricarmen',2,100,'N','H',100,'T','B',200,100,0.25);

INSERT INTO stats
(intel,strenght,charisma,`level`,id_character) 
VALUES
(33,22,333,33,1),(1,1,1,1,2),(75,2000,60,70,3),(9999,20,1,10,4);

INSERT INTO items_types (type)
VALUES("Otros"), 
("Equipable"),
("Consumible"), 
("Clave");

INSERT INTO items (item,cost,consumable,tradeable,weight,image,description,id_item_type)
VALUES("Poción de vida", 25, true, true, 0.2, "health_potion.png", "Una poción que recupera vida", 3),
	("Gafas de sol", 100, false, true, 0.1, "sunglasses.png", "Gafas de sol facheritas", 2),
	("Guijarro", 0, false, false, 0.35, "small_stone.png", "Pequeña piedra que encuentras en el suelo y lo pudes tirar a alguien supongo", 1),
	("Agua de río", 1000, true, false, 0.5, "river_water.png", "Agua del río con propiedades medicinales que recupera energía de vitalidad", 4);

INSERT INTO characters_items (id_character,id_item) VALUES (1,1),(1,3),(1,2),(2,1),(3,2);

INSERT INTO weapons_types(type) VALUES ('Cortante'),('Punzante'),('Contundente');

INSERT INTO armours_types(type) VALUES ('Ligera'),('Mediana'),('Pesada');

INSERT INTO weapons(weapon, damage, quality, rarity, weight, durability, `range`, id_weapon_type)
VALUES('Espada larga',200,30,10,10,500,100,1),
	('Espada corta',100,5,5,10,300,50,1),
	('Lanza',400,100,50,100,1000,400,2),
	('Javelina',500,70,20,50,900,300,2),
	('Estrella del Alba',250,50,700,30,1200,250,3);
INSERT INTO characters_weapons (id_character,id_weapon) VALUES (1,3), (2,2), (3,4), (4,3);	
