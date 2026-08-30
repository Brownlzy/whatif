# What If 翻译映射与剩余清单

生成日期：2026-08-30

## 统计摘要

- 原始 HTML 源文件数（index-2.htm 到 index-159.htm）：158
- 唯一文章数（按英文标题规范化去重）：156
- 严格已翻译唯一文章数（仅按 docs/Part1 与 docs/Web 的 Markdown 文件名匹配）：97
- 严格未翻译唯一文章数：59
- docs/Web 已翻译唯一文章数：57
- 仅在 docs/Part1 命中的旧译文唯一文章数：40
- docs/Part1 Markdown 文件数：73
- docs/Web Markdown 文件数：57

说明：判断已翻译时未读取任何已有译文内容，只读取 Markdown 文件名；英文标题、问题和图片数来自原始 HTML。规范化规则为移除空格、连字符、下划线和非字母数字字符后转小写。

## 重复源文件

| 英文标题 | 规范化键 | 源文件编号 | 源文件 |
|---|---|---|---|
| Bowling Ball | `bowlingball` | 48, 127 | `what-if\index-48.htm, what-if\index-127.htm` |
| Earth-Moon Fire Pole | `earthmoonfirepole` | 2, 159 | `what-if\index-2.htm, what-if\index-159.htm` |

## 严格未命中但疑似已有 Part1 译文

| 编号 | 英文标题 | 规范化键 | Part1 候选文件名 | 编辑距离 | 处理建议 |
|---:|---|---|---|---:|---|
| 11 | Soul Mates | `soulmates` | `Soul_Mate.md` | 1 | 翻译前人工确认是否已覆盖 |
| 25 | Short Answer Section II | `shortanswersectionii` | `Short-Answer_Section.md` | 2 | 翻译前人工确认是否已覆盖 |
| 67 | Twitter Timeline Height | `twittertimelineheight` | `Twitter.md` | 14 | 翻译前人工确认是否已覆盖 |
| 95 | Windshield Raindrops | `windshieldraindrops` | `Raindrop.md` | 11 | 翻译前人工确认是否已覆盖 |

## 剩余未翻译唯一文章

| 顺位 | 编号 | 原文文件 | 英文标题 | 问题 | 图片数 | 建议译文文件 |
|---:|---:|---|---|---|---:|---|
| 42 | 87 | `what-if\index-87.htm` | Rocket Golf | Assuming that you have a spaceship in orbit around the Earth, could you propel your ship to speeds exceeding escape velocity by hitting golf balls in the other direction? If so, how many golf balls would be required to reach the Moon? | 7 | `docs/Web/Rocket_Golf.md` |
| 43 | 88 | `what-if\index-88.htm` | Far-Traveling Objects | In terms of human-made objects, has Voyager 1 travelled the farthest distance? It's certainly the farthest from Earth we know about. But what about the edge of ultracentrifuges, or generator turbines that have been running for years, for example? | 5 | `docs/Web/Far_Traveling_Objects.md` |
| 44 | 89 | `what-if\index-89.htm` | Enforced by Radar | I've occasionally seen "radar enforced" on speed limit signs, and I can't help but ask: How intense would radio waves have to be to stop a car from going over the speed limit, and what would happen if this were attempted? | 4 | `docs/Web/Enforced_by_Radar.md` |
| 45 | 90 | `what-if\index-90.htm` | Soda Sequestration | How much CO2 is contained in the world's stock of bottled fizzy drinks? How much soda would be needed to bring atmospheric CO2 back to preindustrial levels? | 4 | `docs/Web/Soda_Sequestration.md` |
| 46 | 91 | `what-if\index-91.htm` | Tungsten Countertop | How far would a tungsten countertop descend if I dropped it into the Sun? | 3 | `docs/Web/Tungsten_Countertop.md` |
| 47 | 92 | `what-if\index-92.htm` | Great Tree, Great Axe | If all the seas were one sea,What a great sea that would be!If all the trees were one tree,What a great tree that would be!If all the men were one man,What a great man that would be!If all the axes were one axe,What a great axe that would be!And if the great man took the great axe,And cut down the great tree,And let if fall into the great sea,What a great splish-splash that would be! | 7 | `docs/Web/Great_Tree_Great_Axe.md` |
| 48 | 93 | `what-if\index-93.htm` | Faucet Power | I just moved into a new apartment. It includes hot water but I have to pay the electric bill. So being a person on a budget ... what's the best way to use my free faucet to generate electricity? | 7 | `docs/Web/Faucet_Power.md` |
| 49 | 94 | `what-if\index-94.htm` | One-Second Day | What would happen if the Earth's rotation were sped up until a day only lasted one second? | 4 | `docs/Web/One_Second_Day.md` |
| 50 | 95 | `what-if\index-95.htm` | Windshield Raindrops | At what speed would you have to drive for rain to shatter your windshield? | 5 | `docs/Web/Windshield_Raindrops.md` |
| 51 | 96 | `what-if\index-96.htm` | Billion-Story Building | My daughter—age 4.5—maintains she wants a billion-story building. It turns out not only is that hard to help her appreciate this size, I am not at all able to explain all of the other difficulties you'd have to overcome. | 9 | `docs/Web/Billion_Story_Building.md` |
| 52 | 97 | `what-if\index-97.htm` | Pyramid Energy | What took more energy, the building of the Great Pyramid of Giza or the Apollo Mission? If we could convert the energy to build the Great Pyramid, would it be enough to send a rocket to the Moon and back? | 7 | `docs/Web/Pyramid_Energy.md` |
| 53 | 98 | `what-if\index-98.htm` | $2 Undecillion Lawsuit | What if Au Bon Pain lost this lawsuit and had to pay the plaintiff $2 undecillion? | 6 | `docs/Web/2_Undecillion_Lawsuit.md` |
| 54 | 99 | `what-if\index-99.htm` | Burning Pollen | What if you were to somehow ignite the pollen that floats around in the air in spring? Other than being a really bad idea, what effect would it have? | 5 | `docs/Web/Burning_Pollen.md` |
| 55 | 113 | `what-if\index-113.htm` | All the Money | People sometimes say "If I had all the money in the world ..." in order to discuss what they would do if they had no financial constraints. I'm curious, though, what would happen if one person had all of the world's money? | 6 | `docs/Web/All_the_Money.md` |
| 56 | 114 | `what-if\index-114.htm` | Balloon Car | My 12-year-old daughter is proposing an interesting project. She is planning to attach a number of helium balloons to a chair, which in turn would be tethered by means of a rope to a Ferrari. Her 13-year-old friend would then drive the Ferrari around, while she sits in the chair enjoying uninterrupted views of the countryside. Leaving aside the legal and insurance difficulties, my daughter is keen to know the maximum speed that she could expect to attain, and how many helium balloons would be required. | 3 | `docs/Web/Balloon_Car.md` |
| 57 | 115 | `what-if\index-115.htm` | Visit Every State | How fast could you visit all 50 states? | 7 | `docs/Web/Visit_Every_State.md` |
| 58 | 116 | `what-if\index-116.htm` | Antimatter | What if everything was antimatter, EXCEPT Earth? | 3 | `docs/Web/Antimatter.md` |
| 59 | 117 | `what-if\index-117.htm` | Into the Sun | When I was about 8 years old, shoveling snow on a freezing day in Colorado, I wished that I could be instantly transported to the surface of the Sun, just for a nanosecond, then instantly transported back. I figured this would be long enough to warm me up but not long enough to harm me. What would actually happen? | 6 | `docs/Web/Into_the_Sun.md` |
| 60 | 118 | `what-if\index-118.htm` | No-Rules NASCAR | If you stripped away all the rules of car racing and had a contest which was simply to get a human being around a track 200 times as fast as possible, what strategy would win? Let's say the racer has to survive. | 6 | `docs/Web/No_Rules_NASCAR.md` |
| 61 | 119 | `what-if\index-119.htm` | Distant Death | What is the farthest from Earth that any Earth thing has died? | 5 | `docs/Web/Distant_Death.md` |
| 62 | 120 | `what-if\index-120.htm` | Physical Salary | What if people's incomes appeared around them as cash in real time? How much would you need to make to be in real trouble? | 6 | `docs/Web/Physical_Salary.md` |
| 63 | 121 | `what-if\index-121.htm` | Laser Umbrella | Stopping rain from falling on something with an umbrella or a tent is boring. What if you tried to stop rain with a laser that targeted and vaporized each incoming droplet before it could come within ten feet of the ground? | 4 | `docs/Web/Laser_Umbrella.md` |
| 64 | 122 | `what-if\index-122.htm` | Alternate Universe What Ifs | Dispatches from a horrifying alternate universe | 3 | `docs/Web/Alternate_Universe_What_Ifs.md` |
| 65 | 123 | `what-if\index-123.htm` | Frozen Rivers | What would happen if all of the rivers in the US were instantly frozen in the middle of the summer? | 5 | `docs/Web/Frozen_Rivers.md` |
| 66 | 124 | `what-if\index-124.htm` | Lava Lamp | What if I made a lava lamp out of real lava? What could I use as a clear medium? How close could I stand to watch it? | 5 | `docs/Web/Lava_Lamp.md` |
| 67 | 125 | `what-if\index-125.htm` | Fairy Demographics | How many fairies would fly around, if each fairy is born from the first laugh of a child and fairies were immortal? | 4 | `docs/Web/Fairy_Demographics.md` |
| 68 | 126 | `what-if\index-126.htm` | Lunar Swimming | What if there was a lake on the Moon? What would it be like to swim in it? Presuming that it is sheltered in a regular atmosphere, in some giant dome or something. | 5 | `docs/Web/Lunar_Swimming.md` |
| 69 | 128 | `what-if\index-128.htm` | Stairs | If you made an elevator that would go to space (like the one you mentioned in the billion-story building) and built a staircase up (assuming regulated air pressure) about how long would it take to climb to the top? | 4 | `docs/Web/Stairs.md` |
| 70 | 129 | `what-if\index-129.htm` | Tug of War | Would it be possible for two teams in a tug-o-war to overcome the ultimate tensile strength of an iron rod and pull it apart? How big would the teams have to be? | 4 | `docs/Web/Tug_of_War.md` |
| 71 | 130 | `what-if\index-130.htm` | Zippo Phone | What in my pocket actually contains more energy, my Zippo or my smartphone? What would be the best way of getting the energy from one to the other? And since I am already feeling like Bilbo in this one, is there anything else in my pocket that would have unexpected amounts of stored energy? | 4 | `docs/Web/Zippo_Phone.md` |
| 72 | 131 | `what-if\index-131.htm` | Black Hole Moon | What would happen if the Moon were replaced with an equivalently-massed black hole? If it's possible, what would a lunar ("holar"?) eclipse look like? | 5 | `docs/Web/Black_Hole_Moon.md` |
| 73 | 132 | `what-if\index-132.htm` | Snow Removal | I've long thought about putting a flamethrower on the front of a car to melt snow and ice before you drive across it. Now I've realized that a flamethrower is impractical, but what about a high-powered microwave emitter? | 4 | `docs/Web/Snow_Removal.md` |
| 74 | 133 | `what-if\index-133.htm` | Microwaves | I have had a particular problem for as long as I can remember. Any time I attempt to heat left over Chinese food in a microwave, it fails to heat completely through somewhere. Usually the center but not always and usually rice, but often it will be a small section of meat. It's baffling and has made me automatically adjust heating times to over 2 minutes. In most cases this tends to heat the bowl or plate more than the food. So I suppose the question is what is the optimal time to heat left over Chinese food in the microwave, how about an 800 watt microwave? | 5 | `docs/Web/Microwaves.md` |
| 75 | 134 | `what-if\index-134.htm` | Hotter than Average | I saw a sign at a hot springs tub saying "Caution: Water is hotter than average" with water at about 39°C. Although they were presumably trying to say "hotter than the average swimming pool," this got me wondering: What is the average temperature of all water on the Earth’s surface, and how does that temperature compare to 39°C? | 3 | `docs/Web/Hotter_than_Average.md` |
| 76 | 135 | `what-if\index-135.htm` | Flagpole | So, you're falling from a height above the tallest building in your town, and you don't have a parachute. But wait! Partway down the side of that skyscraper there's a flagpole sticking out, sans flag! You angle your descent and grab the pole just long enough to swing around so that when you let go you're now heading back up toward the sky. As gravity slows you and brings you to a halt, you reach the top of the skyscraper, where you reach out and pull yourself to safety. What's the likelihood this could happen? | 4 | `docs/Web/Flagpole.md` |
| 77 | 136 | `what-if\index-136.htm` | Space Burial | I've often joked I'd like to have my remains put into orbit. Not in a "scatter my ashes" sense, but, like, "throw my naked corpse out the airlock" sense. Honestly, my main motivation is to baffle someone in the distant future, but it's an interesting scientific question: what would happen to my body in orbit over the course of years, decades or centuries? | 3 | `docs/Web/Space_Burial.md` |
| 78 | 137 | `what-if\index-137.htm` | Digging Downward | What would happen if I dug straight down, at a speed of 1 foot per second? What would kill me first? | 4 | `docs/Web/Digging_Downward.md` |
| 79 | 138 | `what-if\index-138.htm` | Spiders vs. the Sun | Which has a greater gravitational pull on me: the Sun, or spiders? Granted, the Sun is much bigger, but it is also much further away, and as I learned in high school physics, the gravitational force is proportional to the square of the distance. | 4 | `docs/Web/Spiders_vs_the_Sun.md` |
| 80 | 139 | `what-if\index-139.htm` | New Horizons | What if New Horizons hits my car? | 4 | `docs/Web/New_Horizons.md` |
| 81 | 140 | `what-if\index-140.htm` | Jupiter Submarine | What if you released a submarine into Jupiter's atmosphere? Would it eventually reach a point where it would float? Could it navigate? | 5 | `docs/Web/Jupiter_Submarine.md` |
| 82 | 141 | `what-if\index-141.htm` | Jupiter Descending | If you did fall into Jupiter's atmosphere in a submarine, what would it actually look like? What would you see before you melted or burned up? | 5 | `docs/Web/Jupiter_Descending.md` |
| 83 | 142 | `what-if\index-142.htm` | Proton Earth, Electron Moon | What if the Earth were made entirely of protons, and the Moon were made entirely of electrons? | 4 | `docs/Web/Proton_Earth_Electron_Moon.md` |
| 84 | 143 | `what-if\index-143.htm` | Sunbeam | What if all of the sun's output of visible light were bundled up into a laser-like beam that had a diameter of around 1m once it reaches Earth? | 9 | `docs/Web/Sunbeam.md` |
| 85 | 144 | `what-if\index-144.htm` | Space Jetta | What if I tried to re-enter the atmosphere in my car? (a 2000 VW Jetta TDI). Would it do more environmental damage than it is already apparently doing? | 6 | `docs/Web/Space_Jetta.md` |
| 86 | 145 | `what-if\index-145.htm` | Europa Water Siphon | What if you built a siphon from the oceans on Europa to Earth? Would it flow once it's set up? (We have an idea for selling bottled Europa water.) | 8 | `docs/Web/Europa_Water_Siphon.md` |
| 87 | 146 | `what-if\index-146.htm` | Saliva Pool | How long would it take for a single person to fill up an entire swimming pool with their own saliva? | 10 | `docs/Web/Saliva_Pool.md` |
| 88 | 147 | `what-if\index-147.htm` | Fire From Moonlight | Can you use a magnifying glass and moonlight to light a fire? | 9 | `docs/Web/Fire_From_Moonlight.md` |
| 89 | 148 | `what-if\index-148.htm` | Stop Jupiter | I understand that the New Horizons craft used gravity assist from Jupiter to increase its speed on the way to Pluto. I also understand that by doing this, Jupiter slowed down very slightly. How many flyby runs would it take to stop Jupiter completely? | 5 | `docs/Web/Stop_Jupiter.md` |
| 90 | 149 | `what-if\index-149.htm` | Niagara Straw | What would happen if one tried to funnel Niagara Falls through a straw?[1]This question was in reference to this Amazon review of gummy bears—but before you click, be warned that it describes the reviewer's gastrointestinal response to the candy in rather memorable detail. | 6 | `docs/Web/Niagara_Straw.md` |
| 91 | 150 | `what-if\index-150.htm` | Eat the Sun | What percentage of the Sun's heat (per day) does the population of Earth eat in calories per year? What changes could be made to our diets for the amount of calories to equal the energy of the Sun? | 4 | `docs/Web/Eat_the_Sun.md` |
| 92 | 151 | `what-if\index-151.htm` | Pizza Bird | My boyfriend recently took a flight on a plane with wifi, and while he was up there, wistfully asked if I could send him a pizza. I jokingly sent him a photo of a parrot holding a pizza slice in its beak. Obviously, my boyfriend had to go without pizza until he landed at JFK. But this raised the question: could a bird deliver a standard 20" New York-style cheese pizza in a box? And if so, what kind of bird would it take? | 5 | `docs/Web/Pizza_Bird.md` |
| 93 | 152 | `what-if\index-152.htm` | Tatooine Rainbow | Since rainbows are caused by the refraction of the sunlight by tiny droplets of rainwater, what would rainbow look like on Earth if we had two suns like Tatooine? | 6 | `docs/Web/Tatooine_Rainbow.md` |
| 94 | 153 | `what-if\index-153.htm` | Sun Bug | How many fireflies would it take to match the brightness of the Sun? | 6 | `docs/Web/Sun_Bug.md` |
| 95 | 154 | `what-if\index-154.htm` | Flood Death Valley | Since Death Valley is below sea level could we dig a hole to the ocean and fill it up with water? | 7 | `docs/Web/Flood_Death_Valley.md` |
| 96 | 155 | `what-if\index-155.htm` | Hide the Atmosphere | Earth’s atmosphere is really thin compared to the radius of the Earth. How big a hole do I need to dig before people suffocate? | 4 | `docs/Web/Hide_the_Atmosphere.md` |
| 97 | 156 | `what-if\index-156.htm` | Coast-to-Coast Coasting | What if the entire continental US was on a decreasing slope from West to East. How steep would the slope have to be to sustain the momentum needed to ride a bicycle the entire distance without pedaling? | 6 | `docs/Web/Coast_to_Coast_Coasting.md` |
| 98 | 157 | `what-if\index-157.htm` | Toaster vs. Freezer | Would a toaster still work in a freezer? | 6 | `docs/Web/Toaster_vs_Freezer.md` |
| 99 | 158 | `what-if\index-158.htm` | Electrofishing for Whales | I used to work on a fisheries crew where we would use an electro-fisher backpack to momentarily stun small fish (30 - 100 mm length) so we could scoop them up with nets to identify and measure them. The larger fish tended to be stunned for slightly longer because of their larger surface area but I don't imagine this relationship would be maintained for very large animals. Could you electrofish for a blue whale? At what voltage would you have have to set the e-fisher? | 4 | `docs/Web/Electrofishing_for_Whales.md` |
| 100 | 159 | `what-if\index-159.htm` | Earth-Moon Fire Pole | My son (5y) asked me today: If there were a kind of a fireman's pole from the Moon down to the Earth, how long would it take to slide all the way from the Moon to the Earth? | 21 | `docs/Web/Earth_Moon_Fire_Pole.md` |

## 严格已翻译映射

| 编号 | 原文文件 | 英文标题 | Part1 文件名 | Web 文件名 | 图片数 |
|---:|---|---|---|---|---:|
| 3 | `what-if\index-3.htm` | Relativistic Baseball | `Relativistic_Baseball.md` |  | 5 |
| 4 | `what-if\index-4.htm` | SAT Guessing | `Sat_Guessing.md` |  | 2 |
| 5 | `what-if\index-5.htm` | Yoda | `Yoda.md` |  | 5 |
| 6 | `what-if\index-6.htm` | A Mole of Moles | `A_Mole_Of_Moles.md` |  | 6 |
| 7 | `what-if\index-7.htm` | Robot Apocalypse |  | `Robot_Apocalypse.md` | 6 |
| 8 | `what-if\index-8.htm` | Glass Half Empty | `Glass_Half_Empty.md` |  | 17 |
| 9 | `what-if\index-9.htm` | Everybody Out | `Everybody_Out.md` |  | 3 |
| 10 | `what-if\index-10.htm` | Everybody Jump | `Everybody_Jump.md` |  | 8 |
| 12 | `what-if\index-12.htm` | Cassini |  | `Cassini.md` | 10 |
| 13 | `what-if\index-13.htm` | Droppings |  | `Droppings.md` | 2 |
| 14 | `what-if\index-14.htm` | Raindrop | `Raindrop.md` |  | 8 |
| 15 | `what-if\index-15.htm` | Laser Pointer | `Laser_Pointer.md` |  | 18 |
| 16 | `what-if\index-16.htm` | Short Answer Section | `Short-Answer_Section.md` | `Short_Answer_Section.md` | 4 |
| 17 | `what-if\index-17.htm` | Mariana Trench Explosion |  | `Mariana_Trench_Explosion.md` | 5 |
| 19 | `what-if\index-19.htm` | Green Cows |  | `Green_Cows.md` | 4 |
| 20 | `what-if\index-20.htm` | BB Gun |  | `BB_Gun.md` | 6 |
| 23 | `what-if\index-23.htm` | Machine Gun Jetpack | `Machine-Gun_Jetpack.md` |  | 6 |
| 30 | `what-if\index-30.htm` | Steak Drop | `Steak_Drop.md` |  | 4 |
| 31 | `what-if\index-31.htm` | Spent Fuel Pool | `Spent_Fuel_Pool.md` |  | 4 |
| 32 | `what-if\index-32.htm` | Interplanetary Cessna | `Interplanetary_Cessna.md` |  | 4 |
| 33 | `what-if\index-33.htm` | FedEx Bandwidth | `Fedex_Bandwidth.md` |  | 3 |
| 36 | `what-if\index-36.htm` | Twitter | `Twitter.md` |  | 4 |
| 37 | `what-if\index-37.htm` | Hair Dryer | `Hair_Dryer.md` |  | 22 |
| 41 | `what-if\index-41.htm` | Hockey Puck | `Hockey_Puck.md` |  | 2 |
| 44 | `what-if\index-44.htm` | Longest Sunset | `Longest_Sunset.md` |  | 10 |
| 46 | `what-if\index-46.htm` | High Throw | `High_Throw.md` |  | 11 |
| 49 | `what-if\index-49.htm` | Alien Astronomers | `Alien_Astronomers.md` |  | 4 |
| 50 | `what-if\index-50.htm` | Sunset on the British Empire | `Sunset_On_The_British_Empire.md` |  | 3 |
| 51 | `what-if\index-51.htm` | Sunless Earth | `Sunless_Earth.md` |  | 4 |
| 53 | `what-if\index-53.htm` | Free Fall | `Free_Fall.md` |  | 6 |
| 55 | `what-if\index-55.htm` | Drain the Oceans | `Drain_The_Oceans.md` |  | 11 |
| 57 | `what-if\index-57.htm` | Random Sneeze Call | `Random_Sneeze_Call.md` |  | 4 |
| 60 | `what-if\index-60.htm` | Orbital Speed | `Orbital_Speed.md` |  | 5 |
| 61 | `what-if\index-61.htm` | Updating a Printed Wikipedia | `Updating_A_Printed_Wikipedia.md` |  | 3 |
| 63 | `what-if\index-63.htm` | Speed Bump | `Speed_Bump.md` |  | 4 |
| 64 | `what-if\index-64.htm` | Falling With Helium | `Falling_With_Helium.md` |  | 4 |
| 66 | `what-if\index-66.htm` | Rising Steadily | `Rising_Steadily.md` |  | 6 |
| 69 | `what-if\index-69.htm` | Expanding Earth | `Expanding_Earth.md` |  | 6 |
| 70 | `what-if\index-70.htm` | Little Planet | `Little_Planet.md` |  | 9 |
| 71 | `what-if\index-71.htm` | Facebook of the Dead | `Facebook_Of_The_Dead.md` |  | 5 |
| 73 | `what-if\index-73.htm` | Stirring Tea | `Stirring_Tea.md` |  | 4 |
| 74 | `what-if\index-74.htm` | Loneliest Human | `Loneliest_Human.md` |  | 2 |
| 75 | `what-if\index-75.htm` | Lethal Neutrinos | `Lethal_Neutrinos.md` |  | 5 |
| 100 | `what-if\index-100.htm` | Blood Alcohol |  | `Blood_Alcohol.md` | 5 |
| 101 | `what-if\index-101.htm` | Starlings |  | `Starlings.md` | 4 |
| 102 | `what-if\index-102.htm` | WWII Films |  | `WWII_Films.md` | 4 |
| 103 | `what-if\index-103.htm` | Plastic Dinosaurs |  | `Plastic_Dinosaurs.md` | 6 |
| 104 | `what-if\index-104.htm` | Keyboard Power |  | `Keyboard_Power.md` | 4 |
| 105 | `what-if\index-105.htm` | Vanishing Water |  | `Vanishing_Water.md` | 6 |
| 106 | `what-if\index-106.htm` | Global Snow |  | `Global_Snow.md` | 4 |
| 107 | `what-if\index-107.htm` | Cannibalism |  | `Cannibalism.md` | 3 |
| 108 | `what-if\index-108.htm` | Ink Molecules |  | `Ink_Molecules.md` | 5 |
| 109 | `what-if\index-109.htm` | Letter to Mom |  | `Letter_To_Mom.md` | 4 |
| 110 | `what-if\index-110.htm` | Expensive Shoebox |  | `Expensive_Shoebox.md` | 6 |
| 111 | `what-if\index-111.htm` | Into the Blue |  | `Into_The_Blue.md` | 4 |
| 112 | `what-if\index-112.htm` | Walking New York |  | `Walking_New_York.md` | 4 |

## 全量源文件映射

| 编号 | 状态 | 原文文件 | 英文标题 | 规范化键 | 图片源文件 |
|---:|---|---|---|---|---|
| 2 | todo | `what-if\index-2.htm` | Earth-Moon Fire Pole | `earthmoonfirepole` | grav.png, break.png, slide.png, l1.png, climb.png, oops.png, clamp.png, grab.png, nervous.png, bigcircle.png, bigcircle2.png, bigcircle3.png, stalling.png, fastslow.png, calculate.png, hazysin.png, wait.png, shockwaves.png, parachute.png, drift.png, hazard.png |
| 3 | done | `what-if\index-3.htm` | Relativistic Baseball | `relativisticbaseball` | 01-1.png, 02.png, 03-1.png, 04.png, 05.png |
| 4 | done | `what-if\index-4.htm` | SAT Guessing | `satguessing` | 01.png, 03.png |
| 5 | done | `what-if\index-5.htm` | Yoda | `yoda` | 01-2.png, 02-1.png, 04-1.png, 06.png, yoda_07.png |
| 6 | done | `what-if\index-6.htm` | A Mole of Moles | `amoleofmoles` | moles_too_many.png, moles_star_nosed.png, moles_number_length.png, moles_layers.png, moles_scale.png, moles_rocket.png |
| 7 | done | `what-if\index-7.htm` | Robot Apocalypse | `robotapocalypse` | robot_apocalypse_door.png, robot_apocalypse_threshold.png, robot_apocalypse_comparison.png, robot_apocalypse_phone.png, robot_apocalypse_battlebot.png, robot_apocalypse_end.png |
| 8 | done | `what-if\index-8.htm` | Glass Half Empty | `glasshalfempty` | glass_people.png, glass_three.png, glass_0s.png, glass_50ns.png, glass_150ns.png, glass_400ns.png, glass_1ms.png, glass_2ms.png, glass_5ms.png, glass_8ms.png, glass_10ms.png, glass_20ms.png, glass_500ms.png, glass_1s.png, glass_1_5s.png, glass_10s.png, glass_end.png |
| 9 | done | `what-if\index-9.htm` | Everybody Out | `everybodyout` | everybody_out_plan.png, everybody_out_cargo_van.png, everybody_out_crazy.png |
| 10 | done | `what-if\index-10.htm` | Everybody Jump | `everybodyjump` | everybody_jump_standing.png, everybody_jump_map1.png, everybody_jump_jumping.png, everybody_jump_standing.png, everybody_jump_talking1.png, everybody_jump_talking2.png, everybody_jump_map2.png, everybody_jump_earth.png |
| 11 | done | `what-if\index-11.htm` | Soul Mates | `soulmates` | soulmates_died.png, soulmates_10000.png, soulmates_conveyor.png, soulmates_laptop.png |
| 12 | done | `what-if\index-12.htm` | Cassini | `cassini` | cassini_flip.png, cassini_blank.png, cassini_ice.png, cassini_hadley.png, cassini_tradewinds.png, cassini_horse.png, cassini_climate.png, cassini_hurricanes.png, cassini_cities.png, cassini_alligators.png |
| 13 | done | `what-if\index-13.htm` | Droppings | `droppings` | droppings_setup.png, droppings_car.png |
| 14 | done | `what-if\index-14.htm` | Raindrop | `raindrop` | raindrop_porch.png, raindrop_first_clouds.png, raindrop_tpw.png, raindrop_setup.png, raindrop_emerges.png, raindrop_hits.png, raindrop_floating.png, raindrop_jets.png |
| 15 | done | `what-if\index-15.htm` | Laser Pointer | `laserpointer` | laser_pointer_setup.png, laser_pointer_beam_width.png, laser_pointer_5mw.png, laser_pointer_more_power.png, laser_pointer_1w.png, laser_pointer_more_power.png, laser_pointer_nightsun.png, laser_pointer_more_power.png, laser_pointer_imax.png, laser_pointer_more_power.png, laser_pointer_luxor.png, laser_pointer_luxor_lens.png, laser_pointer_more_power.png, laser_pointer_megawatt.png, laser_pointer_more_power.png, laser_pointer_megawatt_asia.png, laser_pointer_more_power.png, laser_pointer_terawatt.png |
| 16 | done | `what-if\index-16.htm` | Short Answer Section | `shortanswersection` | short_answers_sun.png, short_answers_oneway.png, short_answers_phelps.png, short_answers_headscratch.png |
| 17 | done | `what-if\index-17.htm` | Mariana Trench Explosion | `marianatrenchexplosion` | mariana_map.png, mariana_shallow.png, mariana_sanvu.png, mariana_cat.png, mariana_satisfied.png |
| 18 | done | `what-if\index-18.htm` | Today's topic: Lightning | `todaystopiclightning` | lightning_steps.png, lightning_shadow.png, lightning_shower.png, lightning_boat.png, lightning_graphite.png, lightning_bullet.png, lightning_bios.png |
| 19 | done | `what-if\index-19.htm` | Green Cows | `greencows` | 01-3.png, 02-2.png, 03-2.png, 04-2.png |
| 20 | done | `what-if\index-20.htm` | BB Gun | `bbgun` | bb_1shot.png, bb_army.png, bb_layout.png, bb_moving.png, bb_more.png, bb_asteroid.png |
| 21 | done | `what-if\index-21.htm` | Tie Vote | `tievote` | tie_map.png, tie_map_all.png, tie_coin_toss.png, tie_catastrophe.png |
| 22 | done | `what-if\index-22.htm` | Diamond | `diamond` | diamond_1.png, diamond_11.png, diamond_momentum.png, diamond_3000.png, diamond_99.png, diamond_alien.png |
| 23 | done | `what-if\index-23.htm` | Machine Gun Jetpack | `machinegunjetpack` | jetpack_saturn_v.png, jetpack_squirrel.png, jetpack_500.png, jetpack_twr.png, jetpack_speeding.png, jetpack_mountains.png |
| 24 | done | `what-if\index-24.htm` | Cost of Pennies | `costofpennies` | pennies_notime.png, pennies_food.png, pennies_fitocracy.png, pennies_hack.png, pennies_right.png, pennies_oops.png |
| 25 | done | `what-if\index-25.htm` | Short Answer Section II | `shortanswersectionii` | short_bills.png, short_rent.png, short_damien.png, short_stars.png, short_c4.png |
| 26 | done | `what-if\index-26.htm` | Model Rockets | `modelrockets` | model_suborbital.png, model_acceleration.png, model_space.png, model_pyramid.png |
| 27 | done | `what-if\index-27.htm` | Three Wise Men | `threewisemen` | magi_sirius_walk.png, magi_sirius_realistic_close.png, magi_sirius_realistic.png, magi_venus.png, magi_mars.png, magi_venus_car.png |
| 28 | done | `what-if\index-28.htm` | Leap Seconds | `leapseconds` | leap_tides.png, leap_mass_shift.png, leap_graph.png, leap_strike.png, leap_prince.png, leap_prince_rows.png |
| 29 | done | `what-if\index-29.htm` | Death Rates | `deathrates` | death_comparison.png, death_graph.png, death_everyone.png, death_beatles.png |
| 30 | done | `what-if\index-30.htm` | Steak Drop | `steakdrop` | steak_39km.png, steak_100km.png, steak_250km.png, steak_burning.png |
| 31 | done | `what-if\index-31.htm` | Spent Fuel Pool | `spentfuelpool` | pool_geometry.png, pool_danger.png, pool_safe.png, pool_diver.png |
| 32 | done | `what-if\index-32.htm` | Interplanetary Cessna | `interplanetarycessna` | cessna_plane.png, cessna_pilot.png, cessna_results.png, cessna_icarus.png |
| 33 | done | `what-if\index-33.htm` | FedEx Bandwidth | `fedexbandwidth` | fedex_drives.png, fedex_milk.png, fedex_delivery.png |
| 34 | done | `what-if\index-34.htm` | Hubble | `hubble` | hubble_normal.png, hubble_distortion.png, hubble_pluto.png, hubble_motion_1.png, hubble_motion_2.png, hubble_moon.png, hubble_pluto.png |
| 35 | done | `what-if\index-35.htm` | Ships | `ships` | ships_comparison.png, ships_graph.png, ships_sponges.png |
| 36 | done | `what-if\index-36.htm` | Twitter | `twitter` | twitter_screenshot.png, twitter_volcano.png, twitter_mountains.png, twitter_bird.png |
| 37 | done | `what-if\index-37.htm` | Hair Dryer | `hairdryer` | hair_dryer_equilibrium.png, hair_dryer_18750.png, hair_dryer_breakfast.png, hair_dryer_187500.png, hair_dryer_box600.png, hair_dryer_1875000.png, hair_dryer_box1500.png, hair_dryer_18750000.png, hair_dryer_box2400.png, hair_dryer_187500000.png, hair_dryer_box4500.png, hair_dryer_1875000000.png, hair_dryer_box8000.png, hair_dryer_18750000000.png, hair_dryer_1e11.png, hair_dryer_1e12.png, hair_dryer_1e13.png, hair_dryer_1e14.png, hair_dryer_0.png, hair_dryer_1e16.png, hair_dryer_launch.png, hair_dryer_bill.png |
| 38 | done | `what-if\index-38.htm` | Cornstarch | `cornstarch` | cornstarch_boring.png, cornstarch_clogged.png, cornstarch_floor.png, cornstarch_bitcoins.png, cornstarch_fun.png, cornstarch_toilet.png, cornstarch_lawn.png |
| 39 | done | `what-if\index-39.htm` | Supersonic Stereo | `supersonicstereo` | stereo_waves.png, stereo_standing.png, stereo_message.png |
| 40 | done | `what-if\index-40.htm` | Voyager | `voyager` | voyager_earth.png, voyager_assist.png, voyager_comparison.png, voyager_burn_up.png, voyager_salvage.png |
| 41 | done | `what-if\index-41.htm` | Hockey Puck | `hockeypuck` | goalie_bb_gun.png, goalie_cake.png |
| 42 | done | `what-if\index-42.htm` | Pressure Cooker | `pressurecooker` | pressure_cooker_hmm.png, pressure_cooker_pepsi.png, pressure_cooker_grave.png, pressure_cooker_science.png |
| 43 | done | `what-if\index-43.htm` | Go West | `gowest` | go_west_windmills.png, go_west_setup.png, go_west_clock.png |
| 44 | done | `what-if\index-44.htm` | Longest Sunset | `longestsunset` | sunset_yes.png, sunset_touch.png, sunset_halfrise.png, sunset_not_mitosis.png, sunset_not_egg.png, sunset_not_square.png, sunset_mountain.png, sunset_terminator.png, sunset_terminator_2.png, sunset_spinning.png |
| 45 | done | `what-if\index-45.htm` | Train Loop | `trainloop` | train_loop_comparison.png, train_loop_900.png, train_loop_jet.png, train_loop_900_747.png, train_loop_jet_bottom.png, train_loop_clothoid.png, train_loop_mountain.png, train_loop_biden.png |
| 46 | done | `what-if\index-46.htm` | High Throw | `highthrow` | high_throw_blood.png, high_throw_drumstick.png, high_throw_redirector.png, high_throw_gravity.png, high_throw_giraffe.png, high_throw_3.png, high_throw_5.png, high_throw_10.png, high_throw_14.png, high_throw_16.png, high_throw_balloon.png |
| 47 | done | `what-if\index-47.htm` | ISS Music Video | `issmusicvideo` | hadfield_holes.png, hadfield_spotify.png, hadfield_wonderwall.png |
| 48 | done | `what-if\index-48.htm` | Bowling Ball | `bowlingball` | bowling_scan.png, bowling_texture.png, bowling_throw.png, bowling_dead.png, bowling_holes.png, bowling_holes_collapse.png, bowling_craters.png |
| 49 | done | `what-if\index-49.htm` | Alien Astronomers | `alienastronomers` | life_dot.png, life_twitter.png, life_humans.png, life_sorry.png |
| 50 | done | `what-if\index-50.htm` | Sunset on the British Empire | `sunsetonthebritishempire` | empire_simba.png, empire_map.png, empire_eclipse.png |
| 51 | done | `what-if\index-51.htm` | Sunless Earth | `sunlessearth` | sunless_diagram.png, sunless_bridges.png, sunless_parsnip.png, sunless_freeze.png |
| 52 | done | `what-if\index-52.htm` | Extreme Boating | `extremeboating` | boat_mercury.png, boat_bromine_aluminium.png, boat_large.png, boat_cool.png |
| 53 | done | `what-if\index-53.htm` | Free Fall | `freefall` | freefall_thor.png, freefall_candy.png, freefall_voicemail.png, freefall_extended.png, freefall_wannabe.png, freefall_hotdogs.png |
| 54 | done | `what-if\index-54.htm` | Bouncy Balls | `bouncyballs` | bouncy_thought1.png, bouncy_thought2.png, bouncy_child.png, bouncy_thought4.png |
| 55 | done | `what-if\index-55.htm` | Drain the Oceans | `draintheoceans` | drain_0m.png, drain_50m.png, drain_100m.png, drain_200m.png, drain_500m.png, drain_1km.png, drain_2km.png, drain_3km.png, drain_5km.png, drain_ed.png, drain_nl.png |
| 56 | done | `what-if\index-56.htm` | Drain the Oceans: Part II | `draintheoceanspartii` | mars_curiosity.png, mars_1.png, mars_2.png, mars_3.png, mars_4.png, mars_5.png, mars_6.png, mars_7.png, mars_7_stars.png, mars_8.png, mars_9.png, mars_10.png, mars_11.png, mars_12.png, mars_netherlands.png |
| 57 | done | `what-if\index-57.htm` | Random Sneeze Call | `randomsneezecall` | sneeze_success.png, sneeze_murder.png, sneeze_lightning.png, sneeze_double.png |
| 58 | done | `what-if\index-58.htm` | Restraining an Airplane | `restraininganairplane` | 747_whale.png, 747_fishing.png, 747_single.png, 747_hair.png, 747_whale_hang.png |
| 59 | done | `what-if\index-59.htm` | Dropping a Mountain | `droppingamountain` | mountain_hand.png, mountain_surf.png, mountain_hat.png, mountain_foot.png, mountain_hat.png, mountain_summit.png, mountain_hat.png, mountain_space.png, mountain_hat.png, mountain_hat.png, mountain_hat.png, mountain_higher.png |
| 60 | done | `what-if\index-60.htm` | Orbital Speed | `orbitalspeed` | orbit_tall.png, orbit_wide.png, orbit_x15.png, orbit_nyc.png, orbit_1000.png |
| 61 | done | `what-if\index-61.htm` | Updating a Printed Wikipedia | `updatingaprintedwikipedia` | wiki_count.png, wiki_wrong.png, wiki_sharpies.png |
| 62 | done | `what-if\index-62.htm` | Signs of Life | `signsoflife` | sample_sploosh.png, sample_chemtrails.png, sample_stars.png |
| 63 | done | `what-if\index-63.htm` | Speed Bump | `speedbump` | speedbump_dot.png, speedbump_forces.png, speedbump_flip.png, speedbump_city.png |
| 64 | done | `what-if\index-64.htm` | Falling With Helium | `fallingwithhelium` | balloon_party.png, balloon_fall.png, balloon_float.png, balloon_wolfram.png |
| 65 | done | `what-if\index-65.htm` | Google's Datacenters on Punch Cards | `googlesdatacentersonpunchcards` | google_punchcard.png, google_160kb.png, google_ice.png, google_watchers.png |
| 66 | done | `what-if\index-66.htm` | Rising Steadily | `risingsteadily` | rising_friends.png, rising_giraffe.png, rising_spire.png, rising_deathzone.png, rising_grave.png, rising_redgiant.png |
| 67 | done | `what-if\index-67.htm` | Twitter Timeline Height | `twittertimelineheight` | timeline_intro.png, timeline_earth.png, timeline_future.png, timeline_groups.png, timeline_iono.png, timeline_lbt.png |
| 68 | done | `what-if\index-68.htm` | 500 MPH | `500mph` | wind_pickup.png, wind_pavement.png, wind_lean.png, wind_hypercane.png, wind_asteroid.png |
| 69 | done | `what-if\index-69.htm` | Expanding Earth | `expandingearth` | expanding_jolt.png, expanding_day.png, expanding_rope.png, expanding_lift.png, expanding_water.png, expanding_rings.png |
| 70 | done | `what-if\index-70.htm` | Little Planet | `littleplanet` | asteroid_asteroid.png, asteroid_snake.png, asteroid_potato.png, asteroid_tides.png, asteroid_basketball.png, asteroid_ramp.png, asteroid_orbit.png, asteroid_chaotic.png, asteroid_dunk.png |
| 71 | done | `what-if\index-71.htm` | Facebook of the Dead | `facebookofthedead` | facebook_zombie.png, facebook_cory.png, facebook_early.png, facebook_late.png, facebook_grave.png |
| 72 | done | `what-if\index-72.htm` | The Constant Groundskeeper | `theconstantgroundskeeper` | lawn_cuthere.png, lawn_pope.png, lawn_cougar.png, lawn_cougar_2.png |
| 73 | done | `what-if\index-73.htm` | Stirring Tea | `stirringtea` | tea_light.png, tea_jump.png, tea_horse.png, tea_stir.png |
| 74 | done | `what-if\index-74.htm` | Loneliest Human | `loneliesthuman` | lonely_apollo.png, lonely_finally.png |
| 75 | done | `what-if\index-75.htm` | Lethal Neutrinos | `lethalneutrinos` | neutrinos_hand.png, neutrinos_cngs.png, neutrinos_bomb.png, neutrinos_geometry.png, neutrinos_feather.png |
| 76 | done | `what-if\index-76.htm` | Soda Planet | `sodaplanet` | soda_usworld.png, soda_floor.png, soda_dinosaur.png |
| 77 | done | `what-if\index-77.htm` | Phone Keypad | `phonekeypad` | t9_mmo.png, t9_mom.png, t9_arrested.png, t9_ferret.png, t9_honolulu.png, t9_milk.png, t9_galahad.png, t9_sasha.png, t9_salad.png, t9_puppy.png, t9_poetry.png, t9_tweet.png |
| 78 | done | `what-if\index-78.htm` | Reading Every Book | `readingeverybook` | books_what.png, books_tkamps.png, books_leeasimov.png, books_toomany.png |
| 79 | done | `what-if\index-79.htm` | Growth Rate | `growthrate` | height_deathstar.png, height_chart.png, height_zoom.png, height_extrap.png, height_1.png, height_2.png, height_3.png, height_yoda.png, height_4.png, height_5.png, height_7.png, height_10.png, height_dunk.png, height_coaster.png, height_sad.png |
| 80 | done | `what-if\index-80.htm` | T-rex Calories | `trexcalories` | trex_calendar.png, trex_elephant.png, trex_hipsters.png, trex_mcdonalds.png, trex_hamburgers.png |
| 81 | done | `what-if\index-81.htm` | Lake Tea | `laketea` | tea_bathtub.png, tea_harbor.png, tea_waterbottle.png, tea_boiling.png, tea_nz.png |
| 82 | done | `what-if\index-82.htm` | Pile of Viruses | `pileofviruses` | virus_spoon.png, virus_oil.png, virus_mountain.png, virus_hand.png, virus_floating.png |
| 83 | done | `what-if\index-83.htm` | Catch! | `catch` | catch_up.png, catch_balloon.png, catch_spin.png, catch_thor.png, catch_oz.png |
| 84 | done | `what-if\index-84.htm` | Hitting a comet | `hittingacomet` | rosetta_baseball.png, rosetta_route.png, rosetta_send.png, rosetta_eye.png, rosetta_surgery.png |
| 85 | done | `what-if\index-85.htm` | Star Sand | `starsand` | sand_sd.png, sand_dwarfs.png, sand_red.png, sand_hyper.png, sand_gravel.png, sand_castle.png |
| 86 | done | `what-if\index-86.htm` | Paint the Earth | `painttheearth` | paint_sahara.png, paint_age.png, paint_vote1.png, paint_vote2.png, paint_vote3.png, paint_movies.png |
| 87 | done | `what-if\index-87.htm` | Rocket Golf | `rocketgolf` | golf_annotated.png, golf_120.png, golf_150.png, golf_180.png, golf_237.png, golf_310.png, golf_final.png |
| 88 | done | `what-if\index-88.htm` | Far-Traveling Objects | `fartravelingobjects` | far_van.png, far_tools.png, far_dunno.png, far_iaea.png, far_light.png |
| 89 | done | `what-if\index-89.htm` | Enforced by Radar | `enforcedbyradar` | radar_snowflake.png, radar_phonebill.png, radar_gun.png, radar_aircraft.png |
| 90 | done | `what-if\index-90.htm` | Soda Sequestration | `sodasequestration` | soda_layers.png, soda_graph.png, soda_annoying.png, soda_ground.png |
| 91 | done | `what-if\index-91.htm` | Tungsten Countertop | `tungstencountertop` | sun_diagram.png, sun_bye.png, sun_wine.png |
| 92 | done | `what-if\index-92.htm` | Great Tree, Great Axe | `greattreegreataxe` | ygg_pacific.png, ygg_tree.png, ygg_human.png, ygg_ask.png, ygg_ask2.png, ygg_axe.png, ygg_bike.png |
| 93 | done | `what-if\index-93.htm` | Faucet Power | `faucetpower` | faucet_bath.png, faucet_cost.png, faucet_floors.png, faucet_fountain.png, faucet_baths.png, faucet_line.png, faucet_power.png |
| 94 | done | `what-if\index-94.htm` | One-Second Day | `onesecondday` | day_apart.png, day_polar.png, day_geo.png, day_goodnight.png |
| 95 | done | `what-if\index-95.htm` | Windshield Raindrops | `windshieldraindrops` | rain_speed.png, rain_shock.png, rain_jets.png, rain_impact.png, rain_hail.png |
| 96 | done | `what-if\index-96.htm` | Billion-Story Building | `billionstorybuilding` | billion_pb.png, billion_elevators.png, billion_balloons.png, billion_100.png, billion_100x100.png, billion_100x100x100.png, billion_100x100x100x100.png, billion_100x100x100x100x10.png, billion_final.png |
| 97 | done | `what-if\index-97.htm` | Pyramid Energy | `pyramidenergy` | pyramid_space.png, pyramid_launch.png, pyramid_reverse.png, pyramid_equal.png, pyramid_mines.png, pyramid_dutch.png, pyramid_german.png |
| 98 | done | `what-if\index-98.htm` | $2 Undecillion Lawsuit | `2undecillionlawsuit` | 1ud.png, world.png, gwp.png, crust.png, olson.png, final.png |
| 99 | done | `what-if\index-99.htm` | Burning Pollen | `burningpollen` | hands.png, car.png, stilts.png, eating.png, mushroom.png |
| 100 | done | `what-if\index-100.htm` | Blood Alcohol | `bloodalcohol` | glasses.png, squirrel.png, beer.png, squirrel_2.png, gallon.png |
| 101 | done | `what-if\index-101.htm` | Starlings | `starlings` | collide.png, masks.png, earth.png, birdsun.png |
| 102 | done | `what-if\index-102.htm` | WWII Films | `wwiifilms` | nun.png, hours.png, wait-1.png, documentary.png |
| 103 | done | `what-if\index-103.htm` | Plastic Dinosaurs | `plasticdinosaurs` | bubbly.png, cycle.png, cog.png, cog2.png, fun.png, you.png |
| 104 | done | `what-if\index-104.htm` | Keyboard Power | `keyboardpower` | idea.png, squirrel-1.png, olympics.png, fast.png |
| 105 | done | `what-if\index-105.htm` | Vanishing Water | `vanishingwater` | boat.png, wreck.png, sailboat.png, whale.png, how.png, ocean.png |
| 106 | done | `what-if\index-106.htm` | Global Snow | `globalsnow` | comparison.png, pond.png, board.png, fight.png |
| 107 | done | `what-if\index-107.htm` | Cannibalism | `cannibalism` | proposal.png, squirrel-2.png, bracket.png |
| 108 | done | `what-if\index-108.htm` | Ink Molecules | `inkmolecules` | attention.png, drying.png, number.png, pixels.png, squid.png |
| 109 | done | `what-if\index-109.htm` | Letter to Mom | `lettertomom` | walk.png, ghosts.png, elon.png, lex.png |
| 110 | done | `what-if\index-110.htm` | Expensive Shoebox | `expensiveshoebox` | billion.png, president.png, nuke.png, packing.png, weird.png, check.png |
| 111 | done | `what-if\index-111.htm` | Into the Blue | `intotheblue` | sucks.png, curve.png, try.png, planet.png |
| 112 | done | `what-if\index-112.htm` | Walking New York | `walkingnewyork` | backandforth.png, postal.png, elephants.png, jail.png |
| 113 | done | `what-if\index-113.htm` | All the Money | `allthemoney` | summon.png, scrooge.png, distance.png, mint.png, died.png, zoning.png |
| 114 | done | `what-if\index-114.htm` | Balloon Car | `ballooncar` | running.png, driving.png, arrest.png |
| 115 | done | `what-if\index-115.htm` | Visit Every State | `visiteverystate` | nerd_sniping.png, polar.png, orbits.png, six.png, five.png, truck.png, walked.png |
| 116 | done | `what-if\index-116.htm` | Antimatter | `antimatter` | good.png, questions.png, telescope.png |
| 117 | done | `what-if\index-117.htm` | Into the Sun | `intothesun` | foot.png, sun.png, cells.png, want.png, hope.png, icarus.png |
| 118 | done | `what-if\index-118.htm` | No-Rules NASCAR | `norulesnascar` | daytona.png, profile.png, directions.png, rules.png, fire.png, particle.png |
| 119 | done | `what-if\index-119.htm` | Distant Death | `distantdeath` | usual.png, yet.png, microbe.png, officer.png, alas.png |
| 120 | done | `what-if\index-120.htm` | Physical Salary | `physicalsalary` | plink.png, water.png, 600.png, heavy.png, comparison-1.png, worst.png |
| 121 | done | `what-if\index-121.htm` | Laser Umbrella | `laserumbrella` | no.png, no2.png, ok.png, lasers.png |
| 122 | done | `what-if\index-122.htm` | Alternate Universe What Ifs | `alternateuniversewhatifs` | players-1.png, moon-1.png, harvester-1.png |
| 123 | done | `what-if\index-123.htm` | Frozen Rivers | `frozenrivers` | upside.png, iceto.png, forecast.png, acoe.png, oregon.png |
| 124 | done | `what-if\index-124.htm` | Lava Lamp | `lavalamp` | fear.png, horrible.png, inside.png, volcano.png, more.png |
| 125 | todo | `what-if\index-125.htm` | Fairy Demographics | `fairydemographics` | deathrate.png, bad.png, graph.png, predator.png |
| 126 | todo | `what-if\index-126.htm` | Lunar Swimming | `lunarswimming` | kennedy.png, jump.png, dive.png, slide-1.png, elon-1.png |
| 127 | todo | `what-if\index-127.htm` | Bowling Ball | `bowlingball` | sink.png, cold.png, strike.png |
| 128 | todo | `what-if\index-128.htm` | Stairs | `stairs` | stairs.png, options.png, slink.png, butter.png |
| 129 | todo | `what-if\index-129.htm` | Tug of War | `tugofwar` | dangerous.png, bricks.png, map.png, end.png |
| 130 | todo | `what-if\index-130.htm` | Zippo Phone | `zippophone` | sandwich.png, why.png, knock.png, jump-1.png |
| 131 | todo | `what-if\index-131.htm` | Black Hole Moon | `blackholemoon` | eclipse.png, phases.png, barycenter.png, unit.png, nixon.png |
| 132 | todo | `what-if\index-132.htm` | Snow Removal | `snowremoval` | flamethrower.png, kitchen.png, legal.png, cheetahs.png |
| 133 | todo | `what-if\index-133.htm` | Microwaves | `microwaves` | microwave.png, standing.png, variables.png, same.png, grape.png |
| 134 | todo | `what-if\index-134.htm` | Hotter than Average | `hotterthanaverage` | profound.png, rest.png, domain.png |
| 135 | todo | `what-if\index-135.htm` | Flagpole | `flagpole` | hands-1.png, nope.png, bat.png, bat2.png |
| 136 | todo | `what-if\index-136.htm` | Space Burial | `spaceburial` | naked.png, hbo.png, ice.png |
| 137 | todo | `what-if\index-137.htm` | Digging Downward | `diggingdownward` | kill.png, what.png, horse.png, balrog.png |
| 138 | todo | `what-if\index-138.htm` | Spiders vs. the Sun | `spidersvsthesun` | question.png, force.png, feet.png, planet-1.png |
| 139 | todo | `what-if\index-139.htm` | New Horizons | `newhorizons` | status.png, football.png, herebecars.png, car-2.png |
| 140 | todo | `what-if\index-140.htm` | Jupiter Submarine | `jupitersubmarine` | phase.png, etym.png, falling.png, bowie.png, car-1.png |
| 141 | todo | `what-if\index-141.htm` | Jupiter Descending | `jupiterdescending` | galileo.png, ksp.png, really.png, layers.png, clouds.png |
| 142 | todo | `what-if\index-142.htm` | Proton Earth, Electron Moon | `protonearthelectronmoon` | picture.png, help.png, general.png, problems.png |
| 143 | todo | `what-if\index-143.htm` | Sunbeam | `sunbeam` | maxchanism.png, beam.png, twilight.png, bubble.png, newmoon.png, moon-2.png, brda.png, dawn.png, oops-1.png |
| 144 | todo | `what-if\index-144.htm` | Space Jetta | `spacejetta` | jetta.png, tailpipe.png, problem.png, atmosphere.png, tesla.png, launch.png |
| 145 | todo | `what-if\index-145.htm` | Europa Water Siphon | `europawatersiphon` | straw.png, dresser.png, vacuum.png, balance.png, siphon.png, gravity_wells.png, delivery.png, billboard.png |
| 146 | todo | `what-if\index-146.htm` | Saliva Pool | `salivapool` | question-1.png, envelope.png, bathtub.png, empty.png, ankles.png, knees.png, fingertips.png, waist.png, full.png, party.png |
| 147 | todo | `what-if\index-147.htm` | Fire From Moonlight | `firefrommoonlight` | wrong.png, rabbit.png, wait-2.png, atoc.png, atoc2.png, smoosh.png, etendue.png, linesight.png, astronaut.png |
| 148 | todo | `what-if\index-148.htm` | Stop Jupiter | `stopjupiter` | dontcare.png, y2k.png, accidents.png, burlap.png, truck-1.png |
| 149 | todo | `what-if\index-149.htm` | Niagara Straw | `niagarastraw` | consequences.png, waterjet.png, find.png, yikes.png, mad.png, barrel.png |
| 150 | todo | `what-if\index-150.htm` | Eat the Sun | `eatthesun` | easy.png, actualsize.png, snakemeat.png, franchises.png |
| 151 | todo | `what-if\index-151.htm` | Pizza Bird | `pizzabird` | setup.png, wingtypes.png, pickup.png, mechanism.png, eagle.png |
| 152 | todo | `what-if\index-152.htm` | Tatooine Rainbow | `tatooinerainbow` | double.png, alexander.png, fifth.png, binary.png, trig.png, dorothy.png |
| 153 | todo | `what-if\index-153.htm` | Sun Bug | `sunbug` | bignumbers.png, chart.png, blocked.png, insect.png, solar.png, chart2.png |
| 154 | todo | `what-if\index-154.htm` | Flood Death Valley | `flooddeathvalley` | deathsea.png, dontcare-1.png, notquite.png, thankgod.png, zzyzx.png, nick.png, panel.png |
| 155 | todo | `what-if\index-155.htm` | Hide the Atmosphere | `hidetheatmosphere` | hole.png, cube.png, pressure.png, texas.png |
| 156 | todo | `what-if\index-156.htm` | Coast-to-Coast Coasting | `coasttocoastcoasting` | maui.png, slopes.png, tangent.png, distance-1.png, skiing.png, beach.png |
| 157 | todo | `what-if\index-157.htm` | Toaster vs. Freezer | `toastervsfreezer` | setup-2.png, power.png, relative.png, neg.png, canada.png, antarctica.png |
| 158 | todo | `what-if\index-158.htm` | Electrofishing for Whales | `electrofishingforwhales` | setup-1.png, boat-1.png, arrest-1.png, pond-1.png |
| 159 | todo | `what-if\index-159.htm` | Earth-Moon Fire Pole | `earthmoonfirepole` | grav.png, break.png, slide.png, l1.png, climb.png, oops.png, clamp.png, grab.png, nervous.png, bigcircle.png, bigcircle2.png, bigcircle3.png, stalling.png, fastslow.png, calculate.png, hazysin.png, wait.png, shockwaves.png, parachute.png, drift.png, hazard.png |
