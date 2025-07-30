VEO 3 Video Prompts
All of these are written in JSON format and can be entered into any image model (e.g.
Kling, Seedream, Runway, Midjourney video and Veo 3). You can use them directly on
the model websites or via platforms like Clipyard and Leonardo and offer multiple
models.
1. Pixel Art first person gaming:
{
"description": "A short pixel-art animation presenting a first-person perspective of a
character at the entrance of a dark forest path. The character holds a flaming torch in
one hand and a sword in the other. The path winds down into a verdant valley, where a
quaint village with small houses is nestled. Beyond the valley, a colossal, dark castle
with towering spires is perched atop a rugged mountain, partially shrouded in mist
under a brooding sky. The scene is reminiscent of classic fantasy adventure games.",
"style": "pixel art, retro gaming, fantasy, adventure, atmospheric",
"camera": "first-person perspective, fixed shot, looking forward into the landscape.",
"lighting": "Low light conditions, suggesting evening or night. The primary light source is
the flickering torch in the foreground, casting dynamic orange hues. Subtle ambient
light illuminates the valley and distant castle, creating a mysterious and somewhat
ominous atmosphere.",
"environment": "A dense, dark forest canopy frames the immediate foreground. A
winding dirt path leads through a lush, green valley dotted with a small, spread-out
village. Jagged, dark mountains dominate the background, with an imposing castle
situated on the highest peak.",
"elements": [
"protagonist's hands (visible in first-person view)",
"flaming torch with detailed wooden handle",
"long, sharp fantasy sword with an ornate hilt",
"tall, dark green pine trees lining the path",
"dirt/stone path leading into the valley",
"small, red-roofed village houses",
"rolling green hills and valleys",
"large, multi-towered dark castle",
"rocky mountain terrain",
"wisps of mist or clouds around the castle and mountains",
"dark, purplish-grey sky"
],
"motion": "The most prominent motion is the continuous, natural flickering of the torch
flame. There are also very subtle, almost imperceptible shifts in the mist or clouds
around the distant castle, giving a sense of dynamic atmosphere. The rest of the scene,
including the hands, sword, and landscape, remains static.",
"ending": "The video loops back to its beginning, maintaining the animated scene of
the flickering torch and static environment.",
"text": "none",
"sound": "none (based on the provided video clip)",
"overall_mood": "Adventurous, mysterious, epic, and slightly foreboding. It evokes a
strong sense of a hero's journey or a quest within a fantasy realm.",
"scenes": [
{
"start": 0.0,
"end": 4.0,
"visual": "The entire video presents a continuous, animated pixel-art scene from a
first-person perspective. The protagonist's hands hold a flickering torch and a sword,
framing a path that leads into a valley with a village and a distant castle on a mountain.
The torch flame is constantly in motion, and subtle environmental animations (like mist)
occur.",
"sound": "none"
}
]
}
2. IKEA ad
prompt_name: "IKEA Empty Room Assembly" base_style: "cinematic,
photorealistic, 4K" aspect_ratio: "16:9" room_description: "An empty, large,
sunlit Scandinavian room with white walls and light wood floors." camera_setup:
"A single, fixed, wide-angle shot. The camera does not move for the entire 8-
second duration." key_elements: - "A sealed IKEA box with logo visible"
assembled_elements: - "bed with white duvet" - "yellow IKEA throw blanket" -
"bedside tables" - "lamps" - "wardrobe" - "shelves" - "mirror" - "art" - "rug" -
"curtains" - "potted plants" negative_prompts: ["no people", "no text overlays",
"no distracting music"] timeline: - sequence: 1 timestamp: "00:00-00:01" action:
"In the center of the otherwise empty room, a sealed IKEA box sits on the floor
and begins to tremble gently." audio: "Low, subtle rumbling sound. The echo of a
large, empty room." - sequence: 2 timestamp: "00:01-00:02" action: "The box
seams burst open with a puff of cardboard dust." audio: "A sharp 'POP' sound,
followed by tearing cardboard." - sequence: 3 timestamp: "00:02-00:06" action:
"Hyper-lapse: From the fixed wide perspective, furniture pieces fly out of the box
and assemble themselves, creating all the items from the 'assembled_elements'
list." audio: "A cascade of satisfying, fast-paced ASMR sounds: whirring, clicking,
wood snapping into place." - sequence: 4 timestamp: "00:06-00:08" action: "The
final piece—the yellow throw blanket—gracefully lands on the newly formed
bed. The room is now perfectly furnished and serene. All motion ceases." audio:
"All chaotic sounds stop. A single, soft 'fwoomp' as the blanket lands. The sound
of a furnished, quiet room."
3. ASMR
{
"description": "A 4K ASMR video of a person slicing a dragon fruit on a wooden cutting
board. The dragon fruit is rendered with hyper-realistic detail: vibrant pink skin with
green scale-like tips, slightly waxy texture, and oval shape. It appears organic and juicy,
but slices cleanly into even cross-sections with a sharp kitchen knife. The person’s
hands are gently pressing down, smoothly cutting through the fruit, which reveals a
stark white interior filled with tiny black seeds, glistening with moisture. The cutting
board is polished wood, under soft ambient lighting with a solid black background.",
"style": "cinematic, hyper-realistic, 4K",
"camera": "fixed close-up macro shot focused on the object being sliced",
"lighting": "soft diffused lighting with gentle highlights, creating a calm and relaxing
mood",
"room": "minimalist studio setup with polished wooden cutting board and black
backdrop",
"elements": [
"dragon fruit with vibrant pink skin and green tips",
"sharp stainless steel kitchen knife",
"hands gently pressing and slicing",
"polished wooden cutting board",
"solid black background"
],
"motion": "knife smoothly presses through the fruit, cutting into perfect even slices
that separate and fan out slightly on the board",
"ending": "the final slice falls gently to the board, revealing the full pattern of black-
seeded cross-sections as moisture glistens under the soft light",
"text": "none",
"keywords": [
"16:9",
"ASMR",
"slicing",
"dragon fruit",
"hyper-realistic",
"macro",
"relaxing"
],
"asmr_sounds": [
"clean slicing sound of knife through soft fruit",
"subtle squelch as the fruit separates",
"light thud of slices settling on the board"
],
{
"scenes": [
"start": 0.0,
"end": 2.0,
"visual": "Close-up: a whole dragon fruit resting on a polished wooden board. The
camera lingers on its pink, textured skin under soft lighting.",
"sound": "ambient room tone, faint rustle of hands adjusting position"
},
{
"start": 2.0,
"end": 5.0,
"visual": "The knife presses down slowly, slicing through the skin with minimal
resistance. The first cross-section cleanly separates, revealing a white, seed-filled
interior glistening with moisture.",
"sound": "clean slicing sound, subtle squelch as blade exits the fruit"
},
{
"start": 5.0,
"end": 8.0,
"visual": "Several more slices are cut smoothly, each piece fanning out on the board
as the fruit's interior pattern becomes fully visible. The hands pause gently at the final
slice.",
"sound": "repetitive slicing, faint thud of pieces landing on wood"
}
]
}
4. Lego ad
{ "description": "Cinematic shot of a child's bedroom at night, gently lit by moonlight
streaming through the window. A sealed LEGO box sits on the floor. It begins to shake
subtly, then opens on its own. LEGO bricks fly out silently, assembling mid-air in perfect
sequence to form a glowing spaceship set. The set hovers briefly before settling onto
the floor, fully built. Soft shadows from its glow play across the walls, evoking a sense of
magic and wonder. No text or dialogue.",
"style": "cinematic",
"camera": "fixed wide angle", "lighting": "cool moonlight with warm internal glow from
the LEGO set",
"room": "child’s bedroom at night with soft bedding, a rug, and toys faintly visible in
shadows",
"elements": [ "LEGO box (sealed, brand visible)", "loose LEGO bricks", "spaceship LEGO
set (glowing softly)", "moonlight through window", "child’s bedroom furniture (bed,
nightstand, bookshelves)", "toys and subtle decor" ],
"motion": "box trembles, opens smoothly, bricks levitate and click together mid-air in
rapid but graceful motion",
"ending": "complete glowing LEGO spaceship on the floor, casting soft shadows across
the room",
"text": "none",
"keywords": [ "16:9", "LEGO", "imaginative", "magical realism", "childhood wonder",
"moonlight", "silent magic", "no dialogue", "bedroom scene", "assembly animation" ] }
5. Tennis Ball Spinning Loop
{ "description": "A hyper-real macro tennis ball sits against a black background. It slowly
cracks open like a shell to reveal a surreal spherical interior: a miniature curved clay
court embedded within the felt-lined shell. A female tennis player stands centered in
the middle third.",
"style": "editorial realism",
"camera": "macro static → pivot and dolly-in → lateral tracking to follow spinning ball",
"lighting": "soft top-down editorial lighting with curved, tactile shadows",
"scene": "interior of a spherical tennis ball with a warped clay court and surreal
sportscape", "elements": [ "matte neon-green tennis ball", "white seam detail", "shell-
style lid opening upward", "miniature curved clay court", "floating net", "curved fencing
and ambient lights", "female tennis player centered in middle third", "green felt-lined
interior shell", "spinning tennis ball flying into right third", "macro ball exterior reforming
at end" ],
"motion": "ball cracks open → camera glides in → player strikes ball with grunt → ball
spins toward lens → rotates into original macro position",
"ending": "loop resolves with ball closing seamlessly into its original macro form, same
angle and lighting",
"audio": "no text, only ambient sound and sharp player grunt on impact" }
6. Community Theatre:
{
"description": "A small-town community theater performance of The Legend of Zelda.
The stage is decorated with hand-painted cardboard cutouts of Hyrule’s fields and
castles, with a simple paper Triforce centerpiece. Actors in charming homemade
costumes play Link, Zelda, and Ganon with over-the-top, earnest energy. The whole
production feels like a delightful local effort, with visible stagehands and playful DIY
effects.",
"style": "comedic, theatrical, lo-fi DIY aesthetic",
"camera": "static wide shot from the audience perspective, like a camcorder recording
a school play",
"lighting": "simple, uneven stage lighting with visible spotlights on key characters",
"room": "small community theater with a basic proscenium stage, visible painted
backdrops, and cardboard scenery",
"elements": [
"Link in a green tunic and cap (felt fabric, foam sword and shield)",
"Zelda in a handmade pink and white gown with a paper tiara",
"Ganon in oversized foam armor with a painted pig-mask helmet",
"hand-painted cardboard castle and grassy hills",
"stage props like fake treasure chests and glowing paper 'rupees'",
"visible ropes, pulleys, and stagehands for simple effects"
],
"motion": "actors dramatically act out a 'battle' scene with slow, exaggerated swings;
cardboard rupees are tossed by a stagehand as Link 'collects' them; the Triforce prop is
hoisted with visible wires.",
"ending": "Link, Zelda, and Ganon take an enthusiastic bow as the cardboard Triforce
glows (with a flickering light bulb), drawing polite applause.",
"text": "none",
"keywords": [
"16:9",
"Legend of Zelda",
"community theater",
"DIY",
"stage play",
"comedic"
],
{
"scenes": [
"start": 0.0,
"end": 2.0,
"visual": "Wide shot of the stage: Link stands center stage, cardboard Hyrule scenery
behind him. Zelda appears from stage right, waving grandly as the Triforce centerpiece
glows weakly.",
"sound": "audience murmurs, stage creaks, a faint boombox playing a simple Zelda
theme cover"
},
{
"start": 2.0,
"end": 5.0,
"visual": "Ganon enters in foam armor with a pig-faced helmet. He raises his arms
dramatically as Link swings a foam sword in slow, exaggerated 'battle' motions. A
stagehand tosses green cardboard rupees onto the stage.",
"sound": "audience giggles, thuds of props hitting the floor, enthusiastic but
unpolished acting voices"
},
{
"start": 5.0,
"end": 8.0,
"visual": "Link holds the Triforce overhead triumphantly as Zelda claps beside him.
Ganon dramatically 'falls,' clearly onto a thin crash mat. The three take a bow as the
cardboard scenery wobbles slightly.",
"sound": "light applause from the audience, faint squeak of curtain ropes, one child
yelling 'Go Link!'"
}
]
}
7. Nike trainer
{ "description": "Cinematic shot of a dark, textured backdrop illuminated by cool
directional lighting. The Nike Swoosh hovers midair, glowing faintly. It begins to pulse
with energy, then shatters into thousands of tiny particles. The particles swirl rapidly,
gaining momentum, and begin to form a Nike running shoe midair—assembling piece
by piece in a precise, fluid motion. Once fully formed, the shoe descends gently onto
the surface and flexes subtly, as if infused with life. A single soft footstep echoes before
the scene fades to black.", "style": "cinematic", "camera": "fixed wide angle", "lighting":
"moody, cool-toned with sharp directional contrast on a dark background", "room":
"abstract, textured studio backdrop with no discernible walls or environment",
"elements": [ "floating Nike Swoosh (glowing)", "shattering particles (light-emitting,
swirling)", "Nike running shoe (sleek, modern)", "surface with soft matte texture", "subtle
ambient particles or dust" ], "motion": "Swoosh pulses and explodes into particles,
which swirl and reform into a shoe; the shoe descends and flexes slightly", "ending":
"shoe lands gently, flexes with subtle energy, footstep is heard, then fade to black",
"text": "none", "keywords": [ "16:9", "Nike", "brand reveal", "particle animation", "shoe
assembly", "cinematic", "cool lighting", "precision", "energy" ] }
8. Trojan Horse:
"description": "Handheld selfie shot of a man in full ancient Greek armor on a dusty
road, holding the camera at arm’s length. Behind him, an enormous wooden Trojan
horse is being wheeled toward towering stone city gates. He smirks and delivers a
casual line to the camera, clearly aware of the absurdity of the situation.",
"style": "cinematic, photorealistic, 4K",
"camera": "handheld selfie perspective with slight shake, close focus on the man’s
face with the Trojan horse framed behind him",
"lighting": "warm late-afternoon sunlight, dusty and golden with soft shadows",
"room": "ancient battlefield road leading to massive stone gates with distant soldiers
and primitive wooden carts",
"elements": [
"man in bronze Greek armor (plumed helmet, breastplate, greaves)",
"gigantic wooden Trojan horse with ropes and wooden wheels",
"massive stone city gates in the distance",
"distant silhouettes of soldiers pushing the horse"
],
"motion": "the man adjusts the selfie angle slightly, glances back at the horse, then
smirks and speaks to the camera; background figures push the horse slowly forward",
"ending": "camera holds on the man’s smirk as he winks and freezes mid-expression",
"text": "none",
"keywords": [
"16:9",
"Trojan horse",
"ancient Greece",
"selfie",
"cinematic",
"historical comedy"
],
{
"scenes": [
"start": 0.0,
"end": 2.0,
"visual": "Selfie shot: the man in Greek armor raises the camera, framing himself with
the Trojan horse looming behind him as it creaks forward.",
"sound": "creaking wooden wheels, faint shouting of distant soldiers, light wind"
},
{
"start": 2.0,
"end": 4.0,
"visual": "He glances over his shoulder at the horse, adjusts the camera slightly to
center it in the shot, then smirks knowingly.",
"sound": "light armor clinks as he moves, background chatter muffled"
},
{
"start": 4.0,
"end": 8.0,
"visual": "Looking directly into the camera, he says: 'Just dropping off a totally normal
gift. Definitely not suspicious.' He gives a playful wink as the camera freezes on his
smirk.",
"sound": "casual voice recording tone, creaking horse wheels fading into the
background"
}
]
}
9. Chewy Ad
{ "description": "Cinematic shot of a dew-covered backyard patio at sunrise. A Chewy
box sits in the grass. It bursts open with a soft pop, and pet supplies magically fly into
position around a sunlit outdoor pet lounge. A dog sprints out of the house and happily
sprawls on the new bed.",
"style": "cinematic",
"camera": "wide angle with gentle dolly movement as items assemble",
"lighting": "early morning natural light, golden and dewy",
"room": "grassy backyard with a small stone patio and garden in background",
"elements": [ "Chewy box (logo visible)", "elevated outdoor pet bowls", "plush weather-
resistant dog bed", "dog toys (frisbee, rope, plush)", "bag of dog food (with eco-
packaging)", "hook on fence with leash", "dog (golden retriever)" ],
"motion": "box pops open softly, supplies arc gracefully into position, landing with soft
impacts and precision",
"ending": "dog bounds in from the house, grabs a toy mid-run, then flops onto the bed",
"text": "Chewy", "keywords": [ "16:9", "Chewy", "dog", "backyard reveal", "natural light",
"pet joy", "magical assembly", ] }
10. 2D Scroller:
{
"shot": {
"composition": "side-scrolling 2D view with dynamic foreground and background
layers",
"lens": "pixel-art simulated arcade lens with subtle CRT filter and occasional screen-
shake effects",
"frame_rate": "24fps with impact animations on key frames for hits and explosions",
"camera_movement": "smooth horizontal tracking with sudden shake bursts during
heavy impacts and explosions"
},
"subject": {
"description": "Two stylized pixel characters locked in intense combat: one wearing
futuristic cyber armor with a glowing visor and laser rifle, the other a nimble rogue in
tattered gear dual-wielding pistols.",
"wardrobe": "Cybernetic character: segmented high-tech armor with glowing accents
and energy shield emitters. Rogue character: torn cloak, ammo belts slung across the
chest, light tactical gear for speed.",
"props": "laser rifle with glowing muzzle effects, dual pistols with pixel muzzle flashes,
scattered spent shell casings, intermittent energy shield bursts"
},
"scene": {
"location": "crumbling rooftop of a neon-soaked cyberpunk city",
"time_of_day": "night",
"environment": "pixelated futuristic skyline with parallax scrolling, flickering
holographic billboards, glowing signage, debris and sparks scattered from previous
battles"
},
"visual_details": {
"action": "Characters dive-roll across destructible cover, exchange rapid fire, and use
quick melee strikes between shots. Muzzle flashes illuminate the rooftop as chunks of
pixelated debris fly from gunfire impacts.",
"special_effects": "pixelated explosions with layered frame animation, parallax city
lights shifting with camera motion, screen shake during heavy hits, and brief slow-
motion sequences on critical shots",
"hair_clothing_motion": "Cloaks flutter with frame-by-frame animation as characters
move, hair sways with wind and recoil, adding depth to the retro aesthetic"
},
"cinematography": {
"lighting": "Strobing neon from nearby billboards, mixed with bright muzzle flashes
and subtle ambient rooftop glow. Explosions briefly overexpose frames for dramatic
emphasis.",
"color_palette": "High-contrast neon blues, reds, and purples against dark, shadowed
backgrounds with occasional bursts of bright orange and white from explosions",
"tone": "Intense and chaotic, evoking the adrenaline of a classic arcade boss fight"
},
"audio": {
"music": "Synthwave battle track with heavy pulsing basslines and chiptune overlays
synced to the action",
"ambient": "Low hum of distant city traffic, electrical buzzing from damaged signs,
faint rooftop wind",
"sound_effects": "Pixel-stylized gunfire bursts, sharp ricochets, metallic reload clinks,
heavy explosion booms, and occasional character grunts",
"mix_level": "Music is dominant, driving the pace, with crisp, punchy SFX layered
clearly above ambient sounds"
},
"dialogue": {
"character": "",
"line": "",
"subtitles": false
}
}
11. Apple Advert
Apple Prompt: { "description": "Cinematic wide-angle shot of a modern, dimly lit
creative studio. As morning light spills in, an unopened Apple box on a sleek desk slowly
opens. A MacBook Pro levitates and powers on, syncing with nearby AirPods and a
glowing iPad. Music swells subtly as screens animate with creative projects. Lighting
shifts from cool to warm as the workspace activates. Ends on a serene shot of the artist
beginning their day.",
"style": "cinematic",
"camera": "wide-angle fixed", "lighting": "cool early light shifting to warm morning glow",
"room": "modern creative studio with minimal decor",
"elements": [ "Apple box (unopened)", "MacBook Pro", "AirPods", "iPad (glowing screen)",
"sleek desk", "minimalist chair", "soft morning light through window", "animated screens
with creative work" ],
"motion": "Apple box slowly opens, devices levitate and power on, sync together as
ambient light and music rise",
"ending": "artist enters frame and begins their day at the now-active workspace",
"keywords": [ "16:9", "Apple", "creative", "clean", "modern", "minimalism", "workspace
reveal", "morning light", ] }
12. Third Person Video game
{
"description": "Third-person video game perspective of a female character exploring
the Amalfi Coast. She walks along a sunlit stone pathway overlooking the sparkling blue
sea, with colorful cliffside houses and vibrant flowers framing the scene. The camera
subtly follows behind her as she takes in the scenery.",
"style": "real-time video game graphics, cinematic",
"camera": "third-person over-the-shoulder tracking shot with smooth follow
movement",
"lighting": "bright Mediterranean sunlight with warm highlights and soft shadows",
"room": "outdoor coastal pathway with colorful Amalfi houses, terracotta rooftops,
bougainvillea, and panoramic sea views",
"elements": [
"female video game character in casual summer attire (light dress, sandals, sun hat)",
"stone pathway with wrought iron railings",
"pastel-colored cliffside houses",
"lush flowers and plants (bougainvillea, lemon trees)",
"crystal-clear blue sea stretching into the horizon",
"distant boats and seagulls"
],
"motion": "character slowly walks forward, occasionally glancing toward the sea;
camera subtly pans to reveal sweeping coastal views",
"ending": "the character pauses at a scenic overlook, resting her hands on the railing
as the camera pulls back slightly to reveal the full panorama",
"text": "none",
"keywords": [
"16:9",
"Amalfi Coast",
"video game",
"third-person",
"female character",
"exploration",
"cinematic"
],
{
"scenes": [
"start": 0.0,
"end": 2.0,
"visual": "Third-person view: the female character steps onto a cobblestone pathway
with the blue sea and pastel Amalfi houses in the distance.",
"sound": "gentle footsteps on stone, distant seagulls, soft ocean breeze"
},
{
"start": 2.0,
"end": 4.0,
"visual": "Camera smoothly tracks behind her as she walks past vibrant bougainvillea
and lemon trees, with terracotta rooftops in view.",
"sound": "rustling leaves, faint waves below"
},
{
"start": 4.0,
"end": 8.0,
"visual": "She stops at a scenic overlook, places her hands on the railing, and gazes
out at the sparkling sea as the camera subtly pulls back for a wide shot.",
"sound": "gentle ocean ambiance, soft breeze, distant gulls"
}
]
}
13. Country
US Prompt: { "description": "Cinematic shot of a sunlit white backdrop. A folded
American flag lies still at the center. A gentle breeze stirs its edges. Slowly, the flag
begins to unfold and ripple in elegant slow motion. As it rises, its fabric dissolves into
radiant beams of red, white, and blue light. The streams spiral outward, expanding
across the scene to form a vibrant, growing American city: the Statue of Liberty
emerges, skyscrapers rise, suburban neighborhoods take shape, national monuments
appear, and highways stretch coast to coast. The entire landscape builds with precision
and pride. Finally, the flag reforms, now waving atop a tall flagpole at the heart of the
skyline.", "style": "cinematic", "camera": "fixed wide angle", "lighting": "bright sunlit white
with soft, diffused shadows and glowing light effects", "room": "minimalist abstract
space transitioning into a vast panoramic cityscape", "elements": [ "folded American
flag", "gentle breeze movement", "red, white, and blue light beams", "Statue of Liberty",
"urban skyline (skyscrapers)", "suburban houses", "national monuments (e.g., Capitol
dome, Lincoln Memorial)", "coast-to-coast highways", "flagpole with reformed American
flag" ], "motion": "flag unfolds in slow motion, dissolves into beams of light; cityscape
assembles outward dynamically and precisely; flag reappears and waves at center",
"ending": "fully formed, colorful American city skyline with flag waving proudly at its
center", "text": "none", "keywords": [ "16:9", "American flag", "city reveal", "patriotic",
"Statue of Liberty", "Capitol dome", "national identity", "symbolic animation", "slow
motion", ] }
14. Themed Room Explosion
{ "description": "Photorealistic cinematic shot of an empty white-walled bedroom with
brown hardwood floors and soft daylight streaming in through windows. A sealed
cardboard amazon box sits in the center. It wiggles, then bursts open in a bright, sparkly
puff. The room transforms and assembles itself. No text.", "style": "photorealistic
cinematic", "camera": "fixed wide angle, front-facing for symmetrical reveal", "lighting":
"soft, diffused natural light with subtle glow accents",
"room": "blank bedroom transformed into a Harry Potter sanctuary", "elements": [
"cardboard amazon box (logo visible)", "Harry Potter bedding and pillows", "magical
wand pillows", "dragon plushie" "plushies (Dragon, Harry Potter, Wand, Broomstick)",
"wall art or framed posters of Harry Potter", "floating shelves with harry potter figurines
and broomstick and wand lights and accessories", "vanity with mirror and house plants",
"Broomstick lamp or neon sign", "fluffy floor mat", "harry potter throw pillows" ],
"motion": "box opens, harry potter items explode out and assemble rapidly and
precisely to form a bedroom", "the items methodically move around and assemble
themselves to form the bedroom" "ending": "soft, cozy Harry Potter bedroom glowing
with warmth and charm", "text": "none", "keywords": [ "16:9", "Harry Potter",
"Broomstick", "Wand", "Dragon", "kids bedroom", "fast assembly", "no text",
"photorealistic", "assembly", "cozy" ] }
15. Yeti Vlog
{
"description": "POV shot of a realistic yeti holding a GoPro selfie stick as he walks
along a winding forest path. The style is comedic and lighthearted, resembling a casual
vlog. The camera bobs slightly with each step, capturing the yeti’s large, furry hand
gripping the selfie stick and the dappled sunlight filtering through dense trees. The
forest floor is littered with fallen leaves and exposed roots. After a few steps, the yeti
glances at the camera with a tired but playful expression before stopping and leaning
against a tree.",
"style": "comedic vlog-style, photorealistic 4K",
"camera": "POV GoPro shot with slight bounce, selfie stick framing, occasional glance
toward the lens",
"lighting": "late afternoon dappled sunlight with warm highlights and cool forest
shadows",
"room": "dense woodland path with twisting trees, fallen leaves, and visible roots",
"elements": [
"realistic yeti with white-gray fur",
"GoPro on a selfie stick",
"winding dirt forest path",
"fallen leaves and exposed tree roots",
"dense forest canopy with sunbeams filtering through"
],
"motion": "camera bobs naturally with each step, the yeti glances playfully at the
camera, then stops and leans against a nearby tree",
"ending": "yeti pauses at the tree, panting slightly with an exaggerated tired expression,
then looks back at the camera with a faint grin",
"text": "none",
"keywords": [
"16:9",
"yeti",
"POV",
"GoPro vlog",
"comedic",
"forest",
"lighthearted"
],
{
"scenes": [
"start": 0.0,
"end": 2.5,
"visual": "POV GoPro footage: the camera bobs as the yeti walks along a winding dirt
path. His furry hand grips the selfie stick while fallen leaves crunch underfoot.",
"sound": "ambient forest sounds: birds chirping, leaves rustling, light footstep
crunches"
},
{
"start": 2.5,
"end": 5.0,
"visual": "The yeti glances at the camera mid-walk, raising his furry eyebrows in a
tired but playful expression. Dappled sunlight flickers across his fur.",
"sound": "light breathing, a faint playful grunt, continued forest ambience"
},
{
"start": 5.0,
"end": 8.0,
"visual": "He stops at a large tree, leaning against it with a big huff of exaggerated
exhaustion, then smirks at the camera as if to say 'what a hike.'",
"sound": "deep exhale, light huffing breath, birdsong in the distance"
}
]
}
"