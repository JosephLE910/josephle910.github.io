# AfterWork art asset slots

Default path convention for Plan 02. Put user-provided PNG files in this folder.

Backgrounds are 320x180 PNG in the current generated set:
- home_bg.png (generated)
- balcony_bg.png (generated)
- alley_bg.png (currently generated from the user's stairwell/style references)
- bar_bg.png (generated shell layer: wall, floor, doors, fixed wall decor only)
- yard_bg.png (generated)

Player:
- player_walk.png: sprite sheet, rows `down,left,right,up`, 21x31 per frame, 2 frames per row.
- Or static direction files: player_down.png, player_left.png, player_right.png, player_up.png.

Objects and NPCs:
- home_bed.png, home_desk.png, home_record.png, home_door.png
- balcony_aquarium.png, balcony_fish.png, balcony_plant.png, balcony_door.png
- alley_stairs_up.png, alley_stairs_down.png, alley_bar_sign.png
- bar_counter.png, bar_shelf.png, bar_bottles.png, bar_stool.png, bar_table.png, bar_chair.png, bar_bartender.png, bar_customer.png, bar_door.png
- yard_bench.png, yard_oldchen.png, yard_smoke.png, yard_ashtray.png, yard_door.png

UI art:
- prompt_marker.png, ui_card.png, ui_choice_cursor.png, ui_drink.png

If any file is missing or fails to load, the game keeps the Plan 01 `fillRect` fallback for that visual.
