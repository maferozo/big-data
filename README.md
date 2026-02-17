# big-data
select * from crime_scene where location = "West Hollywood Records";

select * from witnesses where crime_scene_id = 65;

select * from suspects where bandana_color = 'red' and accessory = 'gold watch';

select * from interviews WHERE suspect_id IN (35, 44, 97) and transcript is not NULL;
