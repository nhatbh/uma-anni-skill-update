# Converted Skill Data

### Red Ace (レッドエース)
Slightly swell with the determination to stay number one in the second half of the race.

**Changes:**

Condition: distance_rate>=50&order==1&bashin_diff_behind<=1**@distance_rate>=50&order==2&is_overtake==1**
 Duration: 5

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

						
acceleration: 0.2

								(Target: self, max 1 )

---

### Focused Mind (精神一到)
Moderately increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

**Changes:**

Condition: is_finalcorner==1&corner==0&change_order_onetime<0&order>=~~4~~**3**
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Empress's Pride (エンプレス・プライド)
Moderately increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

**Changes:**

Condition: is_finalcorner==1&corner!=0&order>=~~4~~**3**&change_order_onetime<0
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### 1st Place Kiss☆ (勝利のキッス☆)
Slightly increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

**Changes:**

Condition: is_finalcorner==1&~~corner!=0&~~blocked_side_continuetime>=2&order<=3
 Duration: 5

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

						
acceleration: 0.2

								(Target: self, max 1 )

---

### Introduction to Physiology (introduction：My body)
Moderately recover endurance when conserving energy on a corner in the second half of the race.

**Changes:**

Condition: distance_rate>=50&corner!=0&order>=3&order_rate<=40
 Duration: ~~0~~ -> **4**

						// Cooldown:

						500
 hp_recovery: 0.035

								(Target: self, max 1 )

						
**speed**: **0.15**

								(Target: **self**, max **1** )

---

### V Is for Victory! (全力Vサインッ！)
Refuse to back down from a challenge, moderately increasing velocity on the final straight.

**Changes:**

Precondition: **is_finalcorner==1&blocked_side_continuetime>=2**
 Condition: is_finalcorner==1&corner==0&order<=5~~&blocked_side_continuetime>=2~~
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Clear Heart (クリアハート)
Moderately recover endurance when well-positioned mid-race.

**Changes:**

Condition: phase_random==1&order>=2&order_rate<=40
 Duration: 0

						// Cooldown:

						500
 hp_recovery: ~~0.035~~ -> **0.055**

								(Target: self, max 1 )

---

### Luck Be with Me! (来てください来てください！)
Moderately clear a path forward with the power of divination when the way ahead is jammed late-race.

**Changes:**

Condition: phase>=2&order>=3&blocked_front==1
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### Call Me King (Call me KING)
Increase velocity in a true display of skill with 200m remaining after racing calmly.

**Changes:**

Condition: temptation_count==0&remain_distance<=201&remain_distance>=199&order>=~~5~~**4**&order_rate<=~~60~~**70**
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Shooting Star (シューティングスター)
Ride the momentum and increase velocity after passing another runner toward the front late-race.

**Changes:**

Condition: phase>=2&order>=~~2~~**1**&order_rate<=50&change_order_onetime<0
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### The View from the Lead Is Mine! (先頭の景色は譲らない…！)
Increase velocity by drawing on all remaining strength when in the lead by a fair margin on the final straight.

**Changes:**

Condition: ~~is_finalcorner==1~~**distance_rate>=50**&~~corner==0&~~order==1&bashin_diff_behind>=1
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Lights of Vaudeville (煌星のヴォードヴィル)
Greatly increase velocity with a dazzling display when just breaking out of the pack toward the front on the final straight.

**Changes:**

Condition: is_finalcorner==1&corner==0&order_rate<=30&~~behind_near_lane_time~~**behind_near_lane_time_set1**>=1
 Duration: 5

						// Cooldown:

						500
 speed: 0.45

								(Target: self, max 1 )

---

### Resplendent Red Ace (ブリリアント・レッドエース)
Swell with the determination to stay number one in the second half of the race.

**Changes:**

Condition: distance_rate>=50&order==1&bashin_diff_behind<=1**@distance_rate>=50&order==2&is_overtake==1**
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### Shooting for Victory! (ヴィクトリーショット！)
Increase acceleration with a pow, a wow, and a bang when well-positioned on the final corner.

**Changes:**

Condition: ~~is_finalcorner~~**is_finalcorner_laterhalf**==1&corner!=0&order>=3&order_rate<=~~50~~**40**
 Duration: 4

						// Cooldown:

						500
 acceleration: 0.4

								(Target: self, max 1 )

---

### Where There's a Will, There's a Way (精神一到何事か成らざらん)
Increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

**Changes:**

Condition: is_finalcorner==1&corner==0&change_order_onetime<0&order>=~~4~~**3**
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### You and Me! One-on-One! (タイマン！デッドヒート！)
Increase velocity when passing another runner on the outside toward the back on the final straight.

**Changes:**

Precondition: **is_finalcorner==1&is_behind_in==1&change_order_onetime<0&order_rate>=40**
 Condition: is_finalcorner==1&corner==0~~&is_behind_in==1&change_order_onetime<0&order_rate>=40~~
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### This Dance Is for Vittoria! (ヴィットーリアに捧ぐ舞踏)
Increase velocity with royal brilliance when engaged in a challenge toward the front on the final corner.

**Changes:**

Condition: is_finalcorner==1&~~corner!=0~~**bashin_diff_behind<=1**&~~bashin_diff_infront~~**order**<=**4@is_finalcorner==**1&~~bashin_diff_behind~~**bashin_diff_infront**<=1&~~blocked_side_continuetime>=2&~~order<=4
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Shadow Break (Shadow Break)
Increase velocity with beastly strength when passing another runner on the outside on the final corner or later.

**Changes:**

Precondition: **phase==1&blocked_side_continuetime>=2**
 Condition: is_finalcorner==1&order>=2&order_rate<=75&is_behind_in==1&change_order_onetime<0
 Duration: 5

						// Cooldown:

						500
 speed: ~~0.35~~ -> **0.45**

								(Target: self, max 1 )

						

 
 Condition: **is_finalcorner==1&order>=2&order_rate<=75&is_behind_in==1&change_order_onetime<0**
 Duration: **5**

						// Cooldown:

						**500**
 **speed**: **0.35**

								(Target: **self**, max **1** )

---

### Blazing Pride (ブレイズ・オブ・プライド)
Increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

**Changes:**

Condition: is_finalcorner==1&corner!=0&order>=~~4~~**3**&change_order_onetime<0
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### undefined (尊み☆ﾗｽﾄｽﾊﾟ—(ﾟ∀ﾟ)—ﾄ!)
undefined

**Changes:**

Condition: change_order_up_end_after>=2
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

						
**lane_speed**: **0.035**

								(Target: **self**, max **1** )

---

### ∴win Q.E.D. (∴win Q.E.D.)
Increase velocity by deriving the winning equation when passing another runner toward the front on the final corner.

**Changes:**

Condition: is_finalcorner==1&~~corner!=0&~~change_order_onetime<0&order<=4
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Flashy☆Landing (ひらめき☆ランディング)
Increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

**Changes:**

Condition: is_finalcorner==1&~~corner!=0&~~blocked_side_continuetime>=2&order<=3
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### Blue Rose Closer (ブルーローズチェイサー)
Increase velocity with strong willpower when breaking out of the pack on the final straight.

**Changes:**

Precondition: **is_finalcorner==1&order<=4&change_order_onetime<0**
 Condition: is_finalcorner==1&corner==0~~&order<=4&change_order_onetime<0~~
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### U=ma2 (U=ma2)
Recover endurance when conserving energy on a corner in the second half of the race.

**Changes:**

Condition: distance_rate>=50&corner!=0&order>=3&order_rate<=40
 Duration: ~~0~~ -> **4**

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

						
**speed**: **0.25**

								(Target: **self**, max **1** )

---

### Our Ticket to Win! (勝利のチケットを、君にッ！)
Refuse to back down from a challenge, increasing velocity on the final straight.

**Changes:**

Precondition: **is_finalcorner==1&blocked_side_continuetime>=2**
 Condition: is_finalcorner==1&corner==0&order<=5~~&blocked_side_continuetime>=2~~
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### #LookatCurren (#LookatCurren)
Gain momentum and begin to advance when passing another runner while well-positioned around halfway through the race.

**Changes:**

Condition: distance_rate>=50&distance_rate<=65&order>=~~3~~**2**&order_rate<=40&change_order_onetime<0
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### undefined (姫たるもの、勝利をこの手に)
undefined

**Changes:**

Condition: is_finalcorner==1&corner==0&~~order>=3&order_rate<=70&~~blocked_side_continuetime>=2
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Pure Heart (ピュリティオブハート)
Recover endurance when well-positioned mid-race.

**Changes:**

Condition: phase_random==1&order>=2&order_rate<=40
 Duration: 0

						// Cooldown:

						500
 hp_recovery: ~~0.055~~ -> **0.075**

								(Target: self, max 1 )

---

### SPARKLY☆STARDOM (キラキラ☆STARDOM)
Become empowered against ceding the spotlight when about to lose the lead on a straight mid-race.

**Changes:**

Condition: phase==1&corner==0&order~~==1~~**<=2**&bashin_diff_behind<=1
 Duration: 5

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### Nemesis (Nemesis)
Increase velocity with smoldering ambition when moving up from a position toward the back of the pack on the final corner.

**Changes:**

Condition: is_finalcorner==1&~~corner!=0&~~order_rate>=~~50~~**40**&order_rate<=75&is_overtake==1
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### I See Victory in My Future! (来ます来てます来させます！)
Clear a path forward with the power of divination when the way ahead is jammed late-race.

**Changes:**

Condition: phase>=2&order>=3&blocked_front==1
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### Prideful King (Pride of KING)
Greatly increase velocity in a true display of skill with 200m remaining after racing calmly.

**Changes:**

Condition: temptation_count==0&remain_distance<=201&remain_distance>=199&order>=~~5~~**4**&order_rate<=~~60~~**70**
 Duration: 5

						// Cooldown:

						500
 speed: 0.45

								(Target: self, max 1 )

---

### Certain Victory (絶対は、ボクだ)
Increase velocity with an indomitable fighting spirit when on the heels of another runner toward the front on the final straight.

**Changes:**

Precondition: **is_finalcorner==1&is_overtake==1&order<=5&order_rate<=50&overtake_target_no_order_up_time>=2**
 Condition: is_finalcorner==1&corner==0~~&is_overtake==1&order<=5&order_rate<=50&overtake_target_no_order_up_time>=2~~
 Duration: 5

						// Cooldown:

						500
 speed: ~~0.35~~ -> **0.45**

								(Target: self, max 1 )

---

### Superior Heal (ゲインヒール・スペリアー)
Recover endurance with a gentle light when dropping down toward the back mid-race.

**Changes:**

Condition: phase==1&change_order_onetime>0&order_rate>=40
 Duration: 0

						// Cooldown:

						500
 hp_recovery: ~~0.055~~ -> **0.075**

								(Target: self, max 1 )

---

### Legacy of the Strong (最強の名を懸けて)
Increase velocity when pressured by another runner and running out of energy toward the front on the final corner or later.

**Changes:**

Condition: is_finalcorner==1&hp_per<=~~35~~**45**&order<=3&order_rate<=50&bashin_diff_behind<=1&overtake_target_time>=1
 Duration: ~~5~~ -> **6**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Eternal Moments (薫風、永遠なる瞬間を)
Increase velocity when starting to make a move from a position toward the front mid-race.

**Changes:**

Condition: ~~phase_random~~**phase**==1&order>=3&order_rate<=50&is_overtake==1
 Duration: 5

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### undefined (Drain for rose)
undefined

**Changes:**

Condition: phase==1&~~distance_rate>=50&~~order>=2&order_rate<=50&overtake_target_time>=1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

						
hp_recovery: -0.005

								(Target: ahead, max 18 )

---

### Maverick ◎ (おひとり様◎)
Increase performance when no other runners are using the same strategy.

**Changes:**

Condition: running_style_count_same<=1
 Duration: -0.0001

						// Cooldown:

						0
 speed_stat_up: ~~60~~ -> **80**

								(Target: self, max 1 )

---

### Maverick ○ (おひとり様○)
Moderately increase performance when no other runners are using the same strategy.

**Changes:**

Condition: running_style_count_same<=1
 Duration: -0.0001

						// Cooldown:

						0
 speed_stat_up: ~~40~~ -> **60**

								(Target: self, max 1 )

---

### Competitive Spirit ◎ (対抗意識◎)
Increase performance when at least 5 other runners are using the same strategy.

**Changes:**

Condition: ~~running_style_count_same~~**running_style_count_same_rate**>=~~6~~**40**
 Duration: -0.0001

						// Cooldown:

						0
 power_stat_up: 60

								(Target: self, max 1 )

---

### Competitive Spirit ○ (対抗意識○)
Moderately increase performance when at least 5 other runners are using the same strategy.

**Changes:**

Condition: ~~running_style_count_same~~**running_style_count_same_rate**>=~~6~~**40**
 Duration: -0.0001

						// Cooldown:

						0
 power_stat_up: 40

								(Target: self, max 1 )

---

### Wallflower (引っ込み思案)
Moderately decrease performance when at least 5 other runners are using the same strategy.

**Changes:**

Condition: ~~running_style_count_same~~**running_style_count_same_rate**>=~~6~~**40**
 Duration: -0.0001

						// Cooldown:

						0
 power_stat_up: -40

								(Target: self, max 1 )

---

### Professor of Curvature (弧線のプロフェッサー)
Increase velocity on a corner with skilled turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						30
 speed: 0.35

								(Target: self, max 1 )

---

### Corner Adept ○ (コーナー巧者○)
Slightly increase velocity on a corner with skilled turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						30
 speed: 0.15

								(Target: self, max 1 )

---

### Corner Adept × (コーナー巧者×)
Moderately decrease velocity on a corner with clumsy turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						30
 current_speed: -0.2

								(Target: self, max 1 )

---

### Corner Connoisseur (曲線のソムリエ)
Increase acceleration on a corner with masterful turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						30
 acceleration: 0.4

								(Target: self, max 1 )

---

### Corner Acceleration ○ (コーナー加速○)
Slightly increase acceleration on a corner with masterful turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						30
 acceleration: 0.2

								(Target: self, max 1 )

---

### Corner Acceleration × (コーナー加速×)
Moderately decrease acceleration on a corner with awkward turning.

**Changes:**

Condition: ~~corner_random~~**all_corner_random**==1~~@corner_random==2@corner_random==3@corner_random==4~~
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						30
 acceleration: -0.2

								(Target: self, max 1 )

---

### Beeline Burst (ハヤテ一文字)
Increase velocity on a straight.

**Changes:**

Condition: straight_random==1
 Duration: ~~0.9~~ -> **2.4**

						// Cooldown:

						30
 speed: 0.35

								(Target: self, max 1 )

---

### Straightaway Adept (直線巧者)
Slightly increase velocity on a straight.

**Changes:**

Condition: straight_random==1
 Duration: ~~0.9~~ -> **2.4**

						// Cooldown:

						30
 speed: 0.15

								(Target: self, max 1 )

---

### Rushing Gale! (一陣の風)
Increase acceleration on a straight.

**Changes:**

Condition: straight_random==1
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						30
 acceleration: 0.4

								(Target: self, max 1 )

---

### Straightaway Acceleration (直線加速)
Slightly increase acceleration on a straight.

**Changes:**

Condition: straight_random==1
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						30
 acceleration: 0.2

								(Target: self, max 1 )

---

### Ramp Revulsion (坂苦手)
Moderately increase fatigue on an uphill.

**Changes:**

Condition: ~~slope~~**up_slope_random**==1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: -0.02

								(Target: self, max 1 )

---

### Packphobia (バ群嫌い)
Moderately lose endurance when surrounded.

**Changes:**

Condition: accumulatetime>=2&~~blocked_all_continuetime>=~~**is_surrounded==**1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: -0.02

								(Target: self, max 1 )

---

### Defeatist (あきらめ癖)
Moderately increase urge to give up when positioned around the very back on the final straight.

**Changes:**

Condition: ~~is_finalcorner~~**last_straight_random**==1&~~is_lastspurt==1&straight_random==1&corner==0&~~distance_diff_rate>=75
 Duration: 3

						// Cooldown:

						30
 current_speed: -0.2

								(Target: self, max 1 )

---

### Iron Will (鋼の意志)
Recover endurance when the way ahead is jammed early-race.

**Changes:**

Condition: phase~~==0~~**<=1**&accumulatetime>=5&blocked_front_continuetime>=1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

---

### Lay Low (隠れ蓑)
Slightly recover endurance when the way ahead is jammed early-race.

**Changes:**

Condition: phase~~==0~~**<=1**&accumulatetime>=5&blocked_front_continuetime>=1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

---

### Center Stage (注目の踊り子)
Increase navigation early-race.

**Changes:**

Condition: phase_random==0
 Duration: 3

						// Cooldown:

						500
 lane_speed: ~~0.035~~ -> **0.045**

								(Target: self, max 1 )

---

### Prudent Positioning (ポジションセンス)
Moderately increase navigation early-race.

**Changes:**

Condition: phase_random==0
 Duration: 3

						// Cooldown:

						500
 lane_speed: ~~0.025~~ -> **0.035**

								(Target: self, max 1 )

---

### Unruffled (どこ吹く風)
Recover endurance when surrounded mid-race.

**Changes:**

Condition: phase==1&~~blocked_all_continuetime>=~~**is_surrounded==**1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

---

### Calm in a Crowd (ウマ込み冷静)
Slightly recover endurance when surrounded mid-race.

**Changes:**

Condition: phase==1&~~blocked_all_continuetime>=~~**is_surrounded==**1
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

---

### No Stopping Me! (ノンストップガール)
Increase maneuverability when the way ahead is blocked in the last spurt.

**Changes:**

Condition: ~~blocked_front_continuetime~~**infront_near_lane_time**>=1&is_lastspurt==1&hp_per>=1
 Duration: 3

						// Cooldown:

						30
 acceleration: 0.4

								(Target: self, max 1 )

						
lane_speed: 0.025

								(Target: self, max 1 )

---

### Nimble Navigator (垂れウマ回避)
Slightly increase maneuverability when the way ahead is blocked in the last spurt.

**Changes:**

Condition: ~~blocked_front_continuetime~~**infront_near_lane_time**>=1&is_lastspurt==1&hp_per>=1
 Duration: 3

						// Cooldown:

						30
 acceleration: 0.2

								(Target: self, max 1 )

						
lane_speed: 0.005

								(Target: self, max 1 )

---

### In Body and Mind (全身全霊)
Increase velocity in the last spurt.

**Changes:**

Condition: is_lastspurt==1&phase_random==3
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Homestretch Haste (末脚)
Slightly increase velocity in the last spurt.

**Changes:**

Condition: is_lastspurt==1&phase_random==3
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Taking the Lead (先手必勝)
Increase ability to go to the front early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase==0~~&accumulatetime>=5~~
 Duration: 1.2

						// Cooldown:

						500
 acceleration: 0.4

								(Target: self, max 1 )

---

### Early Lead (先駆け)
Slightly increase ability to go to the front early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase==0~~&accumulatetime>=5~~
 Duration: 1.2

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Calm and Collected (余裕綽々)
Decrease fatigue early-race. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~phase_random~~**phase_laterhalf_random**==0&~~accumulatetime>=5&~~order_rate<=50
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

---

### Stamina to Spare (スタミナキープ)
Slightly decrease fatigue early-race. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~phase_random~~**phase_laterhalf_random**==0&~~accumulatetime>=5&~~order_rate<=50
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

---

### Speed Star (スピードスター)
Increase ability to break out of the pack on the final corner. (Pace Chaser)

**Changes:**

Condition: running_style==2&is_finalcorner_random==1&order_rate<=50
 Duration: ~~1.2~~ -> **1.8**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Prepared to Pass (抜け出し準備)
Slightly increase ability to break out of the pack on the final corner. (Pace Chaser)

**Changes:**

Condition: running_style==2&is_finalcorner_random==1&order_rate<=50
 Duration: ~~1.2~~ -> **1.8**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Fast & Furious (迅速果断)
Increase velocity mid-race. (Late Surger)

**Changes:**

Condition: running_style==3&phase_random==1&order_rate>50
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Position Pilfer (位置取り押し上げ)
Slightly increase velocity mid-race. (Late Surger)

**Changes:**

Condition: running_style==3&phase_random==1&order_rate>50
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Sturm und Drang (疾風怒濤)
Move up in preparation to close the gap late-race. (End Closer)

**Changes:**

Condition: running_style==4&phase_random==2&distance_diff_rate>=~~75~~**50**
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Masterful Gambit (仕掛け抜群)
Slightly move up in preparation to close the gap late-race. (End Closer)

**Changes:**

Condition: running_style==4&phase_random==2&distance_diff_rate>=~~75~~**50**
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Wait-and-See (様子見)
Slightly decrease fatigue when positioned toward the back mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==1&order_rate>50
 Duration: ~~0~~ -> **3**

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### Blinding Flash (電撃の煌めき)
Increase spurting ability when positioned toward the back late-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==2&order_rate>50
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### Gap Closer (詰め寄り)
Slightly increase spurting ability when positioned toward the back late-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==2&order_rate>50
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

						
**acceleration**: **0.05**

								(Target: **self**, max **1** )

---

### Mile Maven (マイルの支配者)
Widen the margin when in the lead early-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==0&accumulatetime>=5&~~order==1~~**order_rate<=50**
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Productive Plan (積極策)
Slightly widen the margin when in the lead early-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==0&accumulatetime>=5&~~order==1~~**order_rate<=50**
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Keen Eye (慧眼)
Decrease fatigue when positioned toward the back early-race. (Mile)

**Changes:**

Condition: distance_type==2&~~phase_random~~**phase_laterhalf_random**==0&~~accumulatetime>=5&~~order_rate>50
 Duration: ~~0~~ -> **3**

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

						
**current_speed**: **-0.2**

								(Target: **ahead**, max **18** )

---

### Watchful Eye (展開窺い)
Slightly decrease fatigue when positioned toward the back early-race. (Mile)

**Changes:**

Condition: distance_type==2&~~phase_random~~**phase_laterhalf_random**==0&~~accumulatetime>=5&~~order_rate>50
 Duration: ~~0~~ -> **3**

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

						
**current_speed**: **-0.05**

								(Target: **ahead**, max **18** )

---

### Trackblazer (切り開く者)
Decrease fatigue when in the lead mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order~~==1~~**<=3**
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

---

### Rosy Outlook (前途洋々)
Slightly decrease fatigue when in the lead mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order~~==1~~**<=3**
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

---

### Killer Tunes (キラーチューン)
Increase positioning ability when positioned toward the front mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order_rate<=50
 Duration: ~~0.9~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Up-Tempo (テンポアップ)
Slightly increase positioning ability when positioned toward the front mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order_rate<=50
 Duration: ~~0.9~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Unyielding (勝利への執念)
Increase ability to fight back when passed by another runner on the final corner. (Medium)

**Changes:**

Condition: distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime>0
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

						
**acceleration**: **0.1**

								(Target: **self**, max **1** )

---

### Steadfast (食い下がり)
Slightly increase ability to fight back when passed by another runner on the final corner. (Medium)

**Changes:**

Condition: distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime>0
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

						
**acceleration**: **0.05**

								(Target: **self**, max **1** )

---

### Adrenaline Rush (火事場のバ鹿力)
Regain the energy to run after exhausting strength. (Long)

**Changes:**

Condition: distance_type==4&~~is_hp_empty_onetime==1~~**hp_per<=30**
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.055

								(Target: self, max 1 )

---

### Extra Tank (別腹タンク)
Slightly regain the energy to run after exhausting strength. (Long)

**Changes:**

Condition: distance_type==4&~~is_hp_empty_onetime==1~~**hp_per<=30**
 Duration: 0

						// Cooldown:

						500
 hp_recovery: 0.015

								(Target: self, max 1 )

---

### Sprint Corners ◎ (短距離コーナー◎)
Moderately increase velocity on a corner. (Sprint)

**Changes:**

Condition: distance_type==1&~~corner_random~~**all_corner_random**==1~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Sprint Corners ○ (短距離コーナー○)
Slightly increase velocity on a corner. (Sprint)

**Changes:**

Condition: distance_type==1&~~corner_random~~**all_corner_random**==1~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Staggering Lead (圧倒的リード)
Increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase==1&bashin_diff_behind>=~~5~~**3**&order==1
 Duration: ~~1.2~~ -> **3**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Huge Lead (大きなリード)
Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase==1&bashin_diff_behind>=~~5~~**3**&order==1
 Duration: ~~1.2~~ -> **3**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Plan X (プランX)
Increase passing ability when positioned toward the front mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&~~phase_random~~**phase_laterhalf_random**==1&order>=2&order_rate<=50
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.4

								(Target: self, max 1 )

---

### Countermeasure (善後策)
Slightly increase passing ability when positioned toward the front mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&~~phase_random~~**phase_laterhalf_random**==1&order>=2&order_rate<=50
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Perfect Prep! (準備万全！)
Prepare to make for the finish line mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==1
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.035

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### Meticulous Measures (仕掛け準備)
Moderately prepare to make for the finish line mid-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==1
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.025

								(Target: self, max 1 )

						
acceleration: 0.2

								(Target: self, max 1 )

---

### Adored by All (悩殺術)
Intimidate runners behind when positioned toward the front early-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==0&~~order~~**order_rate**<=~~3~~**50**&accumulatetime>=5
 Duration: 3

						// Cooldown:

						500
 current_speed: -0.25

								(Target: behind, max 18 )

---

### Intimidate (後方釘付)
Moderately intimidate runners behind when positioned toward the front early-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==0&~~order~~**order_rate**<=~~3~~**50**&accumulatetime>=5
 Duration: 3

						// Cooldown:

						500
 current_speed: -0.2

								(Target: behind, max 18 )

---

### You've Got No Shot (逃亡禁止令)
Cause panic in runners ahead when positioned toward the back early-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==0&order_rate>50&accumulatetime>=5
 Duration: ~~0~~ -> **1.2**

						// Cooldown:

						500
 hp_recovery: -0.03

								(Target: ahead, max 18 )

						
**acceleration**: **-0.2**

								(Target: **ahead**, max **18** )

---

### Stop Right There! (抜け駆け禁止)
Slightly cause panic in runners ahead when positioned toward the back early-race. (Sprint)

**Changes:**

Condition: distance_type==1&phase_random==0&order_rate>50&accumulatetime>=5
 Duration: ~~0~~ -> **1.2**

						// Cooldown:

						500
 hp_recovery: -0.01

								(Target: ahead, max 18 )

						
**acceleration**: **-0.05**

								(Target: **ahead**, max **18** )

---

### Mile Corners ◎ (マイルコーナー◎)
Moderately increase velocity on a corner. (Mile)

**Changes:**

Condition: distance_type==2&~~corner_random~~**all_corner_random**==1~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Mile Corners ○ (マイルコーナー○)
Slightly increase velocity on a corner. (Mile)

**Changes:**

Condition: distance_type==2&~~corner_random~~**all_corner_random**==1~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Changing Gears (ギアチェンジ)
Increase passing ability when positioned toward the front mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==1&order_rate<=50
 Duration: ~~1.2~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Shifting Gears (ギアシフト)
Slightly increase passing ability when positioned toward the front mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==1&order_rate<=50
 Duration: ~~1.2~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Step on the Gas! (アクセル全開！)
Increase acceleration when passing another runner mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase==1&change_order_onetime<0
 Duration: ~~1.2~~ -> **3**

						// Cooldown:

						500
 acceleration: 0.4

								(Target: self, max 1 )

---

### Acceleration (アクセラレーション)
Slightly increase acceleration when passing another runner mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase==1&change_order_onetime<0
 Duration: ~~1.2~~ -> **3**

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Big-Sisterly (姉御肌)
Increase passing ability. (Mile)

**Changes:**

Condition: distance_type==2&is_overtake==1&accumulatetime>=5
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Unyielding Spirit (負けん気)
Slightly increase passing ability. (Mile)

**Changes:**

Condition: distance_type==2&is_overtake==1&accumulatetime>=5
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Greed for Speed (スピードグリード)
Moderately steal velocity from runners behind when in the lead mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==1&order~~==1~~**<=3**
 Duration: 3

						// Cooldown:

						500
 current_speed: -0.2

								(Target: behind, max 5 )

						
speed: 0.25

								(Target: self, max 1 )

---

### Speed Eater (スピードイーター)
Slightly steal velocity from runners behind when in the lead mid-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==1&order~~==1~~**<=3**
 Duration: 3

						// Cooldown:

						500
 current_speed: -0.15

								(Target: behind, max 5 )

						
speed: 0.15

								(Target: self, max 1 )

---

### Battle Formation (布陣)
Dull movement for runners ahead when positioned toward the back early-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==0&order_rate>50&accumulatetime>=~~5~~**3**
 Duration: 3

						// Cooldown:

						500
 acceleration: -0.3

								(Target: ahead, max 18 )

---

### Opening Gambit (布石)
Slightly dull movement for runners ahead when positioned toward the back early-race. (Mile)

**Changes:**

Condition: distance_type==2&phase_random==0&order_rate>50&accumulatetime>=~~5~~**3**
 Duration: 3

						// Cooldown:

						500
 acceleration: -0.1

								(Target: ahead, max 18 )

---

### Medium Corners ◎ (中距離コーナー◎)
Moderately increase velocity on a corner. (Medium)

**Changes:**

Condition: distance_type==3&~~corner_random~~**all_corner_random**==1~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Medium Corners ○ (中距離コーナー○)
Slightly increase velocity on a corner. (Medium)

**Changes:**

Condition: distance_type==3&~~corner_random~~**all_corner_random**==1~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Lightning Step (ライトニングステップ)
Avoid becoming surrounded when positioned toward the back mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order_rate>50
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.035

								(Target: self, max 1 )

						
acceleration: 0.3

								(Target: self, max 1 )

---

### Thunderbolt Step (イナズマステップ)
Moderately avoid becoming surrounded when positioned toward the back mid-race. (Medium)

**Changes:**

Condition: distance_type==3&phase_random==1&order_rate>50
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.025

								(Target: self, max 1 )

						
acceleration: 0.2

								(Target: self, max 1 )

---

### Long Corners ◎ (長距離コーナー◎)
Moderately increase velocity on a corner. (Long)

**Changes:**

Condition: distance_type==4&~~corner_random~~**all_corner_random**==1~~@distance_type==4&corner_random==2@distance_type==4&corner_random==3@distance_type==4&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Long Corners ○ (長距離コーナー○)
Slightly increase velocity on a corner. (Long)

**Changes:**

Condition: distance_type==4&~~corner_random~~**all_corner_random**==1~~@distance_type==4&corner_random==2@distance_type==4&corner_random==3@distance_type==4&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Vanguard Spirit (先陣の心得)
Increase ability to maintain the lead when leading by a large margin mid-race. (Long)

**Changes:**

Condition: distance_type==4&phase_random==1&bashin_diff_behind>=~~3~~**1**&order==1
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Keeping the Lead (リードキープ)
Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Long)

**Changes:**

Condition: distance_type==4&phase_random==1&bashin_diff_behind>=~~3~~**1**&order==1
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Front Runner Corners ◎ (逃げコーナー◎)
Moderately increase velocity on a corner. (Front Runner)

**Changes:**

Condition: running_style==1&~~corner_random~~**all_corner_random**==1~~@running_style==1&corner_random==2@running_style==1&corner_random==3@running_style==1&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Front Runner Corners ○ (逃げコーナー○)
Slightly increase velocity on a corner. (Front Runner)

**Changes:**

Condition: running_style==1&~~corner_random~~**all_corner_random**==1~~@running_style==1&corner_random==2@running_style==1&corner_random==3@running_style==1&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Sixth Sense (シックスセンス)
Avoid becoming surrounded early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase==0&~~blocked_all_continuetime~~**blocked_front_continuetime**>=1**@running_style==1&phase==0&blocked_side_continuetime>=1**
 Duration: 3

						// Cooldown:

						500
 lane_speed: 0.035

								(Target: self, max 1 )

						
**new_unkn_35**: **0.5**

								(Target: **self**, max **1** )

---

### Dodging Danger (危険回避)
Moderately avoid becoming surrounded early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase==0&~~blocked_all_continuetime~~**blocked_front_continuetime**>=1**@running_style==1&phase==0&blocked_side_continuetime>=1**
 Duration: 3

						// Cooldown:

						500
 lane_speed: 0.025

								(Target: self, max 1 )

						
**new_unkn_35**: **0.5**

								(Target: **self**, max **1** )

---

### Leader's Pride (先頭プライド)
Slightly avoid being passed early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase~~==0~~**<=1**&change_order_onetime>0&accumulatetime>=5**@running_style==1&phase<=1&blocked_side_continuetime>=2&accumulatetime>=5**
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Reignition (再燃焼)
Increase acceleration when positioned toward the back mid-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase_random==1&~~order_rate>50~~**order>=2**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.4

								(Target: self, max 1 )

---

### Second Wind (二の矢)
Slightly increase acceleration when positioned toward the back mid-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase_random==1&~~order_rate>50~~**order>=2**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Restart (リスタート)
Slightly startle runners ahead when failing to get a lead early-race. (Front Runner)

**Changes:**

Condition: running_style==1&phase_random==0&~~order_rate>50~~**order>=2**&accumulatetime>=5
 Duration: 3

						// Cooldown:

						500
 acceleration: -0.1

								(Target: ahead, max 18 )

---

### Pace Chaser Corners ◎ (先行コーナー◎)
Moderately increase velocity on a corner. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~corner_random~~**all_corner_random**==1~~@running_style==2&corner_random==2@running_style==2&corner_random==3@running_style==2&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Pace Chaser Corners ○ (先行コーナー○)
Slightly increase velocity on a corner. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~corner_random~~**all_corner_random**==1~~@running_style==2&corner_random==2@running_style==2&corner_random==3@running_style==2&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Technician (技巧派)
Moderately increase ability to navigate smoothly. (Pace Chaser)

**Changes:**

Condition: running_style==2&is_move_lane==1@running_style==2&is_move_lane==2
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						500
 acceleration: 0.3

								(Target: self, max 1 )

---

### Shrewd Step (巧みなステップ)
Slightly increase ability to navigate smoothly. (Pace Chaser)

**Changes:**

Condition: running_style==2&is_move_lane==1@running_style==2&is_move_lane==2
 Duration: ~~1.8~~ -> **3**

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Determined Descent (決意の直滑降)
Moderately improve running on a downhill. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~slope~~**down_slope_random**==~~2~~**1**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.3

								(Target: self, max 1 )

---

### Straight Descent (直滑降)
Slightly improve running on a downhill. (Pace Chaser)

**Changes:**

Condition: running_style==2&~~slope~~**down_slope_random**==~~2~~**1**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Shatterproof (くじけぬ精神)
Moderately increase acceleration when positioned toward the back mid-race. (Pace Chaser)

**Changes:**

Condition: running_style==2&phase_random==1&order_rate>~~50~~**40**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.3

								(Target: self, max 1 )

---

### Tactical Tweak (まき直し)
Slightly increase acceleration when positioned toward the back mid-race. (Pace Chaser)

**Changes:**

Condition: running_style==2&phase_random==1&order_rate>~~50~~**40**
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Later Surger Corners ◎ (差しコーナー◎)
Moderately increase velocity on a corner. (Late Surger)

**Changes:**

Condition: running_style==3&~~corner_random~~**all_corner_random**==1~~@running_style==3&corner_random==2@running_style==3&corner_random==3@running_style==3&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### Late Surger Corners ○ (差しコーナー○)
Slightly increase velocity on a corner. (Late Surger)

**Changes:**

Condition: running_style==3&~~corner_random~~**all_corner_random**==1~~@running_style==3&corner_random==2@running_style==3&corner_random==3@running_style==3&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Hard Worker (努力家)
Moderately increase passing ability. (Late Surger)

**Changes:**

Condition: running_style==3&is_overtake==1&accumulatetime>=5
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 acceleration: 0.3

								(Target: self, max 1 )

---

### Fighter (がんばり屋)
Slightly increase passing ability. (Late Surger)

**Changes:**

Condition: running_style==3&is_overtake==1&accumulatetime>=5
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### 15,000,000 CC (百万バリキ)
Increase velocity on an uphill. (Late Surger)

**Changes:**

Condition: running_style==3&~~slope~~**up_slope_random**==1
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### 1,500,000 CC (十万バリキ)
Slightly increase velocity on an uphill. (Late Surger)

**Changes:**

Condition: running_style==3&~~slope~~**up_slope_random**==1
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### End Closer Corners ◎ (追込コーナー◎)
Moderately increase velocity on a corner. (End Closer)

**Changes:**

Condition: running_style==4&~~corner_random~~**all_corner_random**==1~~@running_style==4&corner_random==2@running_style==4&corner_random==3@running_style==4&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.25

								(Target: self, max 1 )

---

### End Closer Corners ○ (追込コーナー○)
Slightly increase velocity on a corner. (End Closer)

**Changes:**

Condition: running_style==4&~~corner_random~~**all_corner_random**==1~~@running_style==4&corner_random==2@running_style==4&corner_random==3@running_style==4&corner_random==4~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Highlander (登山家)
Slightly improve running on an uphill.

**Changes:**

Condition: ~~slope~~**up_slope_random**==1
 Duration: 3

						// Cooldown:

						500
 acceleration: 0.2

								(Target: self, max 1 )

---

### Uma Stan (ウマ好み)
Slightly increase velocity when close to many runners.

**Changes:**

Condition: near_count~~==4@near_count==~~**>=3&accumulatetime>=**5~~@near_count==6@near_count==7~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### undefined (ウママニア)
undefined

**Changes:**

Condition: near_count~~==4@near_count==~~**>=3&accumulatetime>=**5~~@near_count==6@near_count==7~~
 Duration: 3

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Trending in the Charts! (チャート急上昇！)
Increase velocity when engaged in a challenge mid-race. (Dirt)

**Changes:**

Condition: ground_type==2&phase==1&blocked_side_continuetime>=2
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.35

								(Target: self, max 1 )

---

### Top Pick (レコメンド)
Slightly increase velocity when engaged in a challenge mid-race. (Dirt)

**Changes:**

Condition: ground_type==2&phase==1&blocked_side_continuetime>=2
 Duration: ~~1.8~~ -> **2.4**

						// Cooldown:

						500
 speed: 0.15

								(Target: self, max 1 )

---

### Burning Spirit WIT (アオハル燃焼・賢)
Burn bright with team spirit, increasing strategic navigation in proportion to the total Wit of racing team members early-race.

**Changes:**

Condition: phase_random==0
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.035

								(Target: self, max 1 , scaled: team_wisdom )

						
fov_up: 15

								(Target: self, max 1 , scaled: team_wisdom )

---

### Ignited Spirit WIT (アオハル点火・賢)
Burn bright with team spirit, slightly increasing strategic navigation in proportion to the total Wit of racing team members early-race.

**Changes:**

Condition: phase_random==0
 Duration: ~~3~~ -> **4**

						// Cooldown:

						500
 lane_speed: 0.015

								(Target: self, max 1 , scaled: team_wisdom )

						
fov_up: 5

								(Target: self, max 1 , scaled: team_wisdom )

---

