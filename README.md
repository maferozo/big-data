# big-data
select * from crime_scene where location = "West Hollywood Records";

select * from witnesses where crime_scene_id = 65;

select * from suspects where bandana_color = 'red' and accessory = 'gold watch';

select * from interviews WHERE suspect_id IN (35, 44, 97) and transcript is not NULL;


-- Buscando casos del lugar donde ocurrió el robo
SELECT * from crime_scene where location = 'Blue Note Lounge';

-- Buscando sospechosos que coincidan
SELECT * from suspects where attire = 'trench coat' and scar = 'left cheek';

-- Buscando entrevistas con ID de sospechosos
select * from interviews WHERE suspect_id IN (3, 83) and transcript is not NULL;
