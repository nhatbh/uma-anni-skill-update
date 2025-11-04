# Converted Skill Data

### Red Ace (レッドエース)
Slightly swell with the determination to stay number one in the second half of the race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_rate&gt;=50&order==1&bashin_diff_behind&lt;=1</span>**@distance_rate&gt;=50&order==2&is_overtake==1**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Focused Mind (精神一到)
Moderately increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner==0&change_order_onetime&lt;0&order&gt;=</span>~~4~~**3**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Empress's Pride (エンプレス・プライド)
Moderately increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner!=0&order&gt;=</span>~~4~~**3**<span>&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### 1st Place Kiss☆ (勝利のキッス☆)
Slightly increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&</span>~~corner!=0&~~<span>blocked_side_continuetime&gt;=2&order&lt;=3</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Introduction to Physiology (introduction：My body)
Moderately recover endurance when conserving energy on a corner in the second half of the race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_rate&gt;=50&corner!=0&order&gt;=3&order_rate&lt;=40</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.035</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**speed**: **0.15**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### V Is for Victory! (全力Vサインッ！)
Refuse to back down from a challenge, moderately increasing velocity on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**is_finalcorner==1&blocked_side_continuetime&gt;=2**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&corner==0&order&lt;=5</span>~~&blocked_side_continuetime&gt;=2~~</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Clear Heart (クリアハート)
Moderately recover endurance when well-positioned mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==1&order&gt;=2&order_rate&lt;=40</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: ~~0.035~~ -&gt; **0.055**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Luck Be with Me! (来てください来てください！)
Moderately clear a path forward with the power of divination when the way ahead is jammed late-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase&gt;=2&order&gt;=3&blocked_front==1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Call Me King (Call me KING)
Increase velocity in a true display of skill with 200m remaining after racing calmly.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>temptation_count==0&remain_distance&lt;=201&remain_distance&gt;=199&order&gt;=</span>~~5~~**4**<span>&order_rate&lt;=</span>~~60~~**70**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shooting Star (シューティングスター)
Ride the momentum and increase velocity after passing another runner toward the front late-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase&gt;=2&order&gt;=</span>~~2~~**1**<span>&order_rate&lt;=50&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### The View from the Lead Is Mine! (先頭の景色は譲らない…！)
Increase velocity by drawing on all remaining strength when in the lead by a fair margin on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~is_finalcorner==1~~**distance_rate&gt;=50**<span>&</span>~~corner==0&~~<span>order==1&bashin_diff_behind&gt;=1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Lights of Vaudeville (煌星のヴォードヴィル)
Greatly increase velocity with a dazzling display when just breaking out of the pack toward the front on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner==0&order_rate&lt;=30&</span>~~behind_near_lane_time~~**behind_near_lane_time_set1**<span>&gt;=1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.45</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Resplendent Red Ace (ブリリアント・レッドエース)
Swell with the determination to stay number one in the second half of the race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_rate&gt;=50&order==1&bashin_diff_behind&lt;=1</span>**@distance_rate&gt;=50&order==2&is_overtake==1**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shooting for Victory! (ヴィクトリーショット！)
Increase acceleration with a pow, a wow, and a bang when well-positioned on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~is_finalcorner~~**is_finalcorner_laterhalf**<span>==1&corner!=0&order&gt;=3&order_rate&lt;=</span>~~50~~**40**</strong></div> <div>Duration: <strong><span>4</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Where There's a Will, There's a Way (精神一到何事か成らざらん)
Increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner==0&change_order_onetime&lt;0&order&gt;=</span>~~4~~**3**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### You and Me! One-on-One! (タイマン！デッドヒート！)
Increase velocity when passing another runner on the outside toward the back on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**is_finalcorner==1&is_behind_in==1&change_order_onetime&lt;0&order_rate&gt;=40**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&corner==0</span>~~&is_behind_in==1&change_order_onetime&lt;0&order_rate&gt;=40~~</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### This Dance Is for Vittoria! (ヴィットーリアに捧ぐ舞踏)
Increase velocity with royal brilliance when engaged in a challenge toward the front on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&</span>~~corner!=0~~**bashin_diff_behind&lt;=1**<span>&</span>~~bashin_diff_infront~~**order**<span>&lt;=</span>**4@is_finalcorner==**<span>1&</span>~~bashin_diff_behind~~**bashin_diff_infront**<span>&lt;=1&</span>~~blocked_side_continuetime&gt;=2&~~<span>order&lt;=4</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shadow Break (Shadow Break)
Increase velocity with beastly strength when passing another runner on the outside on the final corner or later.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**phase==1&blocked_side_continuetime&gt;=2**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&order&gt;=2&order_rate&lt;=75&is_behind_in==1&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: ~~0.35~~ -&gt; **0.45**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div><div class="row"><div class="col"> <div>Condition: <strong>**is_finalcorner==1&order&gt;=2&order_rate&lt;=75&is_behind_in==1&change_order_onetime&lt;0**</strong></div> <div>Duration: <strong>**5**</strong>// Cooldown:<strong>**500**</strong></div> <div><span><strong>**speed**: **0.35**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Blazing Pride (ブレイズ・オブ・プライド)
Increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner!=0&order&gt;=</span>~~4~~**3**<span>&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### undefined (尊み☆ﾗｽﾄｽﾊﾟ—(ﾟ∀ﾟ)—ﾄ!)
undefined

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>change_order_up_end_after&gt;=2</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**lane_speed**: **0.035**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### ∴win Q.E.D. (∴win Q.E.D.)
Increase velocity by deriving the winning equation when passing another runner toward the front on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&</span>~~corner!=0&~~<span>change_order_onetime&lt;0&order&lt;=4</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Flashy☆Landing (ひらめき☆ランディング)
Increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&</span>~~corner!=0&~~<span>blocked_side_continuetime&gt;=2&order&lt;=3</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Blue Rose Closer (ブルーローズチェイサー)
Increase velocity with strong willpower when breaking out of the pack on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**is_finalcorner==1&order&lt;=4&change_order_onetime&lt;0**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&corner==0</span>~~&order&lt;=4&change_order_onetime&lt;0~~</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### U=ma2 (U=ma2)
Recover endurance when conserving energy on a corner in the second half of the race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_rate&gt;=50&corner!=0&order&gt;=3&order_rate&lt;=40</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**speed**: **0.25**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Our Ticket to Win! (勝利のチケットを、君にッ！)
Refuse to back down from a challenge, increasing velocity on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**is_finalcorner==1&blocked_side_continuetime&gt;=2**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&corner==0&order&lt;=5</span>~~&blocked_side_continuetime&gt;=2~~</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### #LookatCurren (#LookatCurren)
Gain momentum and begin to advance when passing another runner while well-positioned around halfway through the race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_rate&gt;=50&distance_rate&lt;=65&order&gt;=</span>~~3~~**2**<span>&order_rate&lt;=40&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### undefined (姫たるもの、勝利をこの手に)
undefined

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&corner==0&</span>~~order&gt;=3&order_rate&lt;=70&~~<span>blocked_side_continuetime&gt;=2</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Pure Heart (ピュリティオブハート)
Recover endurance when well-positioned mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==1&order&gt;=2&order_rate&lt;=40</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: ~~0.055~~ -&gt; **0.075**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### SPARKLY☆STARDOM (キラキラ☆STARDOM)
Become empowered against ceding the spotlight when about to lose the lead on a straight mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase==1&corner==0&order</span>~~==1~~**&lt;=2**<span>&bashin_diff_behind&lt;=1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Nemesis (Nemesis)
Increase velocity with smoldering ambition when moving up from a position toward the back of the pack on the final corner.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&</span>~~corner!=0&~~<span>order_rate&gt;=</span>~~50~~**40**<span>&order_rate&lt;=75&is_overtake==1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### I See Victory in My Future! (来ます来てます来させます！)
Clear a path forward with the power of divination when the way ahead is jammed late-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase&gt;=2&order&gt;=3&blocked_front==1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Prideful King (Pride of KING)
Greatly increase velocity in a true display of skill with 200m remaining after racing calmly.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>temptation_count==0&remain_distance&lt;=201&remain_distance&gt;=199&order&gt;=</span>~~5~~**4**<span>&order_rate&lt;=</span>~~60~~**70**</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.45</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Certain Victory (絶対は、ボクだ)
Increase velocity with an indomitable fighting spirit when on the heels of another runner toward the front on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"><div>Precondition: <strong>**is_finalcorner==1&is_overtake==1&order&lt;=5&order_rate&lt;=50&overtake_target_no_order_up_time&gt;=2**</strong></div> <div>Condition: <strong><span>is_finalcorner==1&corner==0</span>~~&is_overtake==1&order&lt;=5&order_rate&lt;=50&overtake_target_no_order_up_time&gt;=2~~</strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: ~~0.35~~ -&gt; **0.45**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Superior Heal (ゲインヒール・スペリアー)
Recover endurance with a gentle light when dropping down toward the back mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase==1&change_order_onetime&gt;0&order_rate&gt;=40</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: ~~0.055~~ -&gt; **0.075**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Legacy of the Strong (最強の名を懸けて)
Increase velocity when pressured by another runner and running out of energy toward the front on the final corner or later.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_finalcorner==1&hp_per&lt;=</span>~~35~~**45**<span>&order&lt;=3&order_rate&lt;=50&bashin_diff_behind&lt;=1&overtake_target_time&gt;=1</span></strong></div> <div>Duration: <strong>~~5~~ -&gt; **6**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Eternal Moments (薫風、永遠なる瞬間を)
Increase velocity when starting to make a move from a position toward the front mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~phase_random~~**phase**<span>==1&order&gt;=3&order_rate&lt;=50&is_overtake==1</span></strong></div> <div>Duration: <strong><span>5</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### undefined (Drain for rose)
undefined

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase==1&</span>~~distance_rate&gt;=50&~~<span>order&gt;=2&order_rate&lt;=50&overtake_target_time&gt;=1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>hp_recovery</span>: <span>-0.005</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div></div> </div></div>

---

### Maverick ◎ (おひとり様◎)
Increase performance when no other runners are using the same strategy.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style_count_same&lt;=1</span></strong></div> <div>Duration: <strong><span>-0.0001</span></strong>// Cooldown:<strong><span>0</span></strong></div> <div><span><strong><span>speed_stat_up</span>: ~~60~~ -&gt; **80**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Maverick ○ (おひとり様○)
Moderately increase performance when no other runners are using the same strategy.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style_count_same&lt;=1</span></strong></div> <div>Duration: <strong><span>-0.0001</span></strong>// Cooldown:<strong><span>0</span></strong></div> <div><span><strong><span>speed_stat_up</span>: ~~40~~ -&gt; **60**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Competitive Spirit ◎ (対抗意識◎)
Increase performance when at least 5 other runners are using the same strategy.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~running_style_count_same~~**running_style_count_same_rate**<span>&gt;=</span>~~6~~**40**</strong></div> <div>Duration: <strong><span>-0.0001</span></strong>// Cooldown:<strong><span>0</span></strong></div> <div><span><strong><span>power_stat_up</span>: <span>60</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Competitive Spirit ○ (対抗意識○)
Moderately increase performance when at least 5 other runners are using the same strategy.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~running_style_count_same~~**running_style_count_same_rate**<span>&gt;=</span>~~6~~**40**</strong></div> <div>Duration: <strong><span>-0.0001</span></strong>// Cooldown:<strong><span>0</span></strong></div> <div><span><strong><span>power_stat_up</span>: <span>40</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Wallflower (引っ込み思案)
Moderately decrease performance when at least 5 other runners are using the same strategy.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~running_style_count_same~~**running_style_count_same_rate**<span>&gt;=</span>~~6~~**40**</strong></div> <div>Duration: <strong><span>-0.0001</span></strong>// Cooldown:<strong><span>0</span></strong></div> <div><span><strong><span>power_stat_up</span>: <span>-40</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Professor of Curvature (弧線のプロフェッサー)
Increase velocity on a corner with skilled turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Corner Adept ○ (コーナー巧者○)
Slightly increase velocity on a corner with skilled turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Corner Adept × (コーナー巧者×)
Moderately decrease velocity on a corner with clumsy turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Corner Connoisseur (曲線のソムリエ)
Increase acceleration on a corner with masterful turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Corner Acceleration ○ (コーナー加速○)
Slightly increase acceleration on a corner with masterful turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Corner Acceleration × (コーナー加速×)
Moderately decrease acceleration on a corner with awkward turning.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~corner_random~~**all_corner_random**<span>==1</span>~~@corner_random==2@corner_random==3@corner_random==4~~</strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>-0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Beeline Burst (ハヤテ一文字)
Increase velocity on a straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>straight_random==1</span></strong></div> <div>Duration: <strong>~~0.9~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Straightaway Adept (直線巧者)
Slightly increase velocity on a straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>straight_random==1</span></strong></div> <div>Duration: <strong>~~0.9~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Rushing Gale! (一陣の風)
Increase acceleration on a straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>straight_random==1</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Straightaway Acceleration (直線加速)
Slightly increase acceleration on a straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>straight_random==1</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Ramp Revulsion (坂苦手)
Moderately increase fatigue on an uphill.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~slope~~**up_slope_random**<span>==1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>-0.02</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Packphobia (バ群嫌い)
Moderately lose endurance when surrounded.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>accumulatetime&gt;=2&</span>~~blocked_all_continuetime&gt;=~~**is_surrounded==**<span>1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>-0.02</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Defeatist (あきらめ癖)
Moderately increase urge to give up when positioned around the very back on the final straight.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~is_finalcorner~~**last_straight_random**<span>==1&</span>~~is_lastspurt==1&straight_random==1&corner==0&~~<span>distance_diff_rate&gt;=75</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Iron Will (鋼の意志)
Recover endurance when the way ahead is jammed early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase</span>~~==0~~**&lt;=1**<span>&accumulatetime&gt;=5&blocked_front_continuetime&gt;=1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Lay Low (隠れ蓑)
Slightly recover endurance when the way ahead is jammed early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase</span>~~==0~~**&lt;=1**<span>&accumulatetime&gt;=5&blocked_front_continuetime&gt;=1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Center Stage (注目の踊り子)
Increase navigation early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==0</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: ~~0.035~~ -&gt; **0.045**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Prudent Positioning (ポジションセンス)
Moderately increase navigation early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==0</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: ~~0.025~~ -&gt; **0.035**</strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Unruffled (どこ吹く風)
Recover endurance when surrounded mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase==1&</span>~~blocked_all_continuetime&gt;=~~**is_surrounded==**<span>1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Calm in a Crowd (ウマ込み冷静)
Slightly recover endurance when surrounded mid-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase==1&</span>~~blocked_all_continuetime&gt;=~~**is_surrounded==**<span>1</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### No Stopping Me! (ノンストップガール)
Increase maneuverability when the way ahead is blocked in the last spurt.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~blocked_front_continuetime~~**infront_near_lane_time**<span>&gt;=1&is_lastspurt==1&hp_per&gt;=1</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>lane_speed</span>: <span>0.025</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Nimble Navigator (垂れウマ回避)
Slightly increase maneuverability when the way ahead is blocked in the last spurt.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~blocked_front_continuetime~~**infront_near_lane_time**<span>&gt;=1&is_lastspurt==1&hp_per&gt;=1</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>30</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>lane_speed</span>: <span>0.005</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### In Body and Mind (全身全霊)
Increase velocity in the last spurt.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_lastspurt==1&phase_random==3</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Homestretch Haste (末脚)
Slightly increase velocity in the last spurt.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>is_lastspurt==1&phase_random==3</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Taking the Lead (先手必勝)
Increase ability to go to the front early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase==0</span>~~&accumulatetime&gt;=5~~</strong></div> <div>Duration: <strong><span>1.2</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Early Lead (先駆け)
Slightly increase ability to go to the front early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase==0</span>~~&accumulatetime&gt;=5~~</strong></div> <div>Duration: <strong><span>1.2</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Calm and Collected (余裕綽々)
Decrease fatigue early-race. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~phase_random~~**phase_laterhalf_random**<span>==0&</span>~~accumulatetime&gt;=5&~~<span>order_rate&lt;=50</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Stamina to Spare (スタミナキープ)
Slightly decrease fatigue early-race. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~phase_random~~**phase_laterhalf_random**<span>==0&</span>~~accumulatetime&gt;=5&~~<span>order_rate&lt;=50</span></strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Speed Star (スピードスター)
Increase ability to break out of the pack on the final corner. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&is_finalcorner_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **1.8**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Prepared to Pass (抜け出し準備)
Slightly increase ability to break out of the pack on the final corner. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&is_finalcorner_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **1.8**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Fast & Furious (迅速果断)
Increase velocity mid-race. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&phase_random==1&order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Position Pilfer (位置取り押し上げ)
Slightly increase velocity mid-race. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&phase_random==1&order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Sturm und Drang (疾風怒濤)
Move up in preparation to close the gap late-race. (End Closer)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==4&phase_random==2&distance_diff_rate&gt;=</span>~~75~~**50**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Masterful Gambit (仕掛け抜群)
Slightly move up in preparation to close the gap late-race. (End Closer)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==4&phase_random==2&distance_diff_rate&gt;=</span>~~75~~**50**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Wait-and-See (様子見)
Slightly decrease fatigue when positioned toward the back mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==1&order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Blinding Flash (電撃の煌めき)
Increase spurting ability when positioned toward the back late-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==2&order_rate&gt;50</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Gap Closer (詰め寄り)
Slightly increase spurting ability when positioned toward the back late-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==2&order_rate&gt;50</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.05**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Mile Maven (マイルの支配者)
Widen the margin when in the lead early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==0&accumulatetime&gt;=5&</span>~~order==1~~**order_rate&lt;=50**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Productive Plan (積極策)
Slightly widen the margin when in the lead early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==0&accumulatetime&gt;=5&</span>~~order==1~~**order_rate&lt;=50**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Keen Eye (慧眼)
Decrease fatigue when positioned toward the back early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&</span>~~phase_random~~**phase_laterhalf_random**<span>==0&</span>~~accumulatetime&gt;=5&~~<span>order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**current_speed**: **-0.2**</strong>(Target: **ahead**, max **18**</span> )</div></div> </div></div>

---

### Watchful Eye (展開窺い)
Slightly decrease fatigue when positioned toward the back early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&</span>~~phase_random~~**phase_laterhalf_random**<span>==0&</span>~~accumulatetime&gt;=5&~~<span>order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**current_speed**: **-0.05**</strong>(Target: **ahead**, max **18**</span> )</div></div> </div></div>

---

### Trackblazer (切り開く者)
Decrease fatigue when in the lead mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order</span>~~==1~~**&lt;=3**</strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Rosy Outlook (前途洋々)
Slightly decrease fatigue when in the lead mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order</span>~~==1~~**&lt;=3**</strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Killer Tunes (キラーチューン)
Increase positioning ability when positioned toward the front mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~0.9~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Up-Tempo (テンポアップ)
Slightly increase positioning ability when positioned toward the front mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~0.9~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Unyielding (勝利への執念)
Increase ability to fight back when passed by another runner on the final corner. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime&gt;0</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.1**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Steadfast (食い下がり)
Slightly increase ability to fight back when passed by another runner on the final corner. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime&gt;0</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**acceleration**: **0.05**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Adrenaline Rush (火事場のバ鹿力)
Regain the energy to run after exhausting strength. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&</span>~~is_hp_empty_onetime==1~~**hp_per&lt;=30**</strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.055</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Extra Tank (別腹タンク)
Slightly regain the energy to run after exhausting strength. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&</span>~~is_hp_empty_onetime==1~~**hp_per&lt;=30**</strong></div> <div>Duration: <strong><span>0</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Sprint Corners ◎ (短距離コーナー◎)
Moderately increase velocity on a corner. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Sprint Corners ○ (短距離コーナー○)
Slightly increase velocity on a corner. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Staggering Lead (圧倒的リード)
Increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase==1&bashin_diff_behind&gt;=</span>~~5~~**3**<span>&order==1</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Huge Lead (大きなリード)
Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase==1&bashin_diff_behind&gt;=</span>~~5~~**3**<span>&order==1</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Plan X (プランX)
Increase passing ability when positioned toward the front mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&</span>~~phase_random~~**phase_laterhalf_random**<span>==1&order&gt;=2&order_rate&lt;=50</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Countermeasure (善後策)
Slightly increase passing ability when positioned toward the front mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&</span>~~phase_random~~**phase_laterhalf_random**<span>==1&order&gt;=2&order_rate&lt;=50</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Perfect Prep! (準備万全！)
Prepare to make for the finish line mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==1</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.035</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Meticulous Measures (仕掛け準備)
Moderately prepare to make for the finish line mid-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==1</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.025</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Adored by All (悩殺術)
Intimidate runners behind when positioned toward the front early-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==0&</span>~~order~~**order_rate**<span>&lt;=</span>~~3~~**50**<span>&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.25</span></strong>(Target: <span>behind</span>, max <span>18</span></span> )</div></div> </div></div>

---

### Intimidate (後方釘付)
Moderately intimidate runners behind when positioned toward the front early-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==0&</span>~~order~~**order_rate**<span>&lt;=</span>~~3~~**50**<span>&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.2</span></strong>(Target: <span>behind</span>, max <span>18</span></span> )</div></div> </div></div>

---

### You've Got No Shot (逃亡禁止令)
Cause panic in runners ahead when positioned toward the back early-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==0&order_rate&gt;50&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **1.2**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>-0.03</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div><div><span><strong>**acceleration**: **-0.2**</strong>(Target: **ahead**, max **18**</span> )</div></div> </div></div>

---

### Stop Right There! (抜け駆け禁止)
Slightly cause panic in runners ahead when positioned toward the back early-race. (Sprint)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==1&phase_random==0&order_rate&gt;50&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~0~~ -&gt; **1.2**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>hp_recovery</span>: <span>-0.01</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div><div><span><strong>**acceleration**: **-0.05**</strong>(Target: **ahead**, max **18**</span> )</div></div> </div></div>

---

### Mile Corners ◎ (マイルコーナー◎)
Moderately increase velocity on a corner. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Mile Corners ○ (マイルコーナー○)
Slightly increase velocity on a corner. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Changing Gears (ギアチェンジ)
Increase passing ability when positioned toward the front mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shifting Gears (ギアシフト)
Slightly increase passing ability when positioned toward the front mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==1&order_rate&lt;=50</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Step on the Gas! (アクセル全開！)
Increase acceleration when passing another runner mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase==1&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Acceleration (アクセラレーション)
Slightly increase acceleration when passing another runner mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase==1&change_order_onetime&lt;0</span></strong></div> <div>Duration: <strong>~~1.2~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Big-Sisterly (姉御肌)
Increase passing ability. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&is_overtake==1&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Unyielding Spirit (負けん気)
Slightly increase passing ability. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&is_overtake==1&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Greed for Speed (スピードグリード)
Moderately steal velocity from runners behind when in the lead mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==1&order</span>~~==1~~**&lt;=3**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.2</span></strong>(Target: <span>behind</span>, max <span>5</span></span> )</div><div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Speed Eater (スピードイーター)
Slightly steal velocity from runners behind when in the lead mid-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==1&order</span>~~==1~~**&lt;=3**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>current_speed</span>: <span>-0.15</span></strong>(Target: <span>behind</span>, max <span>5</span></span> )</div><div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Battle Formation (布陣)
Dull movement for runners ahead when positioned toward the back early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==0&order_rate&gt;50&accumulatetime&gt;=</span>~~5~~**3**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>-0.3</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div></div> </div></div>

---

### Opening Gambit (布石)
Slightly dull movement for runners ahead when positioned toward the back early-race. (Mile)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==2&phase_random==0&order_rate&gt;50&accumulatetime&gt;=</span>~~5~~**3**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>-0.1</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div></div> </div></div>

---

### Medium Corners ◎ (中距離コーナー◎)
Moderately increase velocity on a corner. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Medium Corners ○ (中距離コーナー○)
Slightly increase velocity on a corner. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Lightning Step (ライトニングステップ)
Avoid becoming surrounded when positioned toward the back mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.035</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Thunderbolt Step (イナズマステップ)
Moderately avoid becoming surrounded when positioned toward the back mid-race. (Medium)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==3&phase_random==1&order_rate&gt;50</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.025</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Long Corners ◎ (長距離コーナー◎)
Moderately increase velocity on a corner. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==4&corner_random==2@distance_type==4&corner_random==3@distance_type==4&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Long Corners ○ (長距離コーナー○)
Slightly increase velocity on a corner. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@distance_type==4&corner_random==2@distance_type==4&corner_random==3@distance_type==4&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Vanguard Spirit (先陣の心得)
Increase ability to maintain the lead when leading by a large margin mid-race. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&phase_random==1&bashin_diff_behind&gt;=</span>~~3~~**1**<span>&order==1</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Keeping the Lead (リードキープ)
Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Long)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>distance_type==4&phase_random==1&bashin_diff_behind&gt;=</span>~~3~~**1**<span>&order==1</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Front Runner Corners ◎ (逃げコーナー◎)
Moderately increase velocity on a corner. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==1&corner_random==2@running_style==1&corner_random==3@running_style==1&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Front Runner Corners ○ (逃げコーナー○)
Slightly increase velocity on a corner. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==1&corner_random==2@running_style==1&corner_random==3@running_style==1&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Sixth Sense (シックスセンス)
Avoid becoming surrounded early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase==0&</span>~~blocked_all_continuetime~~**blocked_front_continuetime**<span>&gt;=1</span>**@running_style==1&phase==0&blocked_side_continuetime&gt;=1**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.035</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**new_unkn_35**: **0.5**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Dodging Danger (危険回避)
Moderately avoid becoming surrounded early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase==0&</span>~~blocked_all_continuetime~~**blocked_front_continuetime**<span>&gt;=1</span>**@running_style==1&phase==0&blocked_side_continuetime&gt;=1**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.025</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div><div><span><strong>**new_unkn_35**: **0.5**</strong>(Target: **self**, max **1**</span> )</div></div> </div></div>

---

### Leader's Pride (先頭プライド)
Slightly avoid being passed early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase</span>~~==0~~**&lt;=1**<span>&change_order_onetime&gt;0&accumulatetime&gt;=5</span>**@running_style==1&phase&lt;=1&blocked_side_continuetime&gt;=2&accumulatetime&gt;=5**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Reignition (再燃焼)
Increase acceleration when positioned toward the back mid-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase_random==1&</span>~~order_rate&gt;50~~**order&gt;=2**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.4</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Second Wind (二の矢)
Slightly increase acceleration when positioned toward the back mid-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase_random==1&</span>~~order_rate&gt;50~~**order&gt;=2**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Restart (リスタート)
Slightly startle runners ahead when failing to get a lead early-race. (Front Runner)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==1&phase_random==0&</span>~~order_rate&gt;50~~**order&gt;=2**<span>&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>-0.1</span></strong>(Target: <span>ahead</span>, max <span>18</span></span> )</div></div> </div></div>

---

### Pace Chaser Corners ◎ (先行コーナー◎)
Moderately increase velocity on a corner. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==2&corner_random==2@running_style==2&corner_random==3@running_style==2&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Pace Chaser Corners ○ (先行コーナー○)
Slightly increase velocity on a corner. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==2&corner_random==2@running_style==2&corner_random==3@running_style==2&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Technician (技巧派)
Moderately increase ability to navigate smoothly. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&is_move_lane==1@running_style==2&is_move_lane==2</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shrewd Step (巧みなステップ)
Slightly increase ability to navigate smoothly. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&is_move_lane==1@running_style==2&is_move_lane==2</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **3**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Determined Descent (決意の直滑降)
Moderately improve running on a downhill. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~slope~~**down_slope_random**<span>==</span>~~2~~**1**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Straight Descent (直滑降)
Slightly improve running on a downhill. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&</span>~~slope~~**down_slope_random**<span>==</span>~~2~~**1**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Shatterproof (くじけぬ精神)
Moderately increase acceleration when positioned toward the back mid-race. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&phase_random==1&order_rate&gt;</span>~~50~~**40**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Tactical Tweak (まき直し)
Slightly increase acceleration when positioned toward the back mid-race. (Pace Chaser)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==2&phase_random==1&order_rate&gt;</span>~~50~~**40**</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Later Surger Corners ◎ (差しコーナー◎)
Moderately increase velocity on a corner. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==3&corner_random==2@running_style==3&corner_random==3@running_style==3&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Late Surger Corners ○ (差しコーナー○)
Slightly increase velocity on a corner. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==3&corner_random==2@running_style==3&corner_random==3@running_style==3&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Hard Worker (努力家)
Moderately increase passing ability. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&is_overtake==1&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.3</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Fighter (がんばり屋)
Slightly increase passing ability. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&is_overtake==1&accumulatetime&gt;=5</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### 15,000,000 CC (百万バリキ)
Increase velocity on an uphill. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&</span>~~slope~~**up_slope_random**<span>==1</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### 1,500,000 CC (十万バリキ)
Slightly increase velocity on an uphill. (Late Surger)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==3&</span>~~slope~~**up_slope_random**<span>==1</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### End Closer Corners ◎ (追込コーナー◎)
Moderately increase velocity on a corner. (End Closer)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==4&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==4&corner_random==2@running_style==4&corner_random==3@running_style==4&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.25</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### End Closer Corners ○ (追込コーナー○)
Slightly increase velocity on a corner. (End Closer)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>running_style==4&</span>~~corner_random~~**all_corner_random**<span>==1</span>~~@running_style==4&corner_random==2@running_style==4&corner_random==3@running_style==4&corner_random==4~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Highlander (登山家)
Slightly improve running on an uphill.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong>~~slope~~**up_slope_random**<span>==1</span></strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>acceleration</span>: <span>0.2</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Uma Stan (ウマ好み)
Slightly increase velocity when close to many runners.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>near_count</span>~~==4@near_count==~~**&gt;=3&accumulatetime&gt;=**<span>5</span>~~@near_count==6@near_count==7~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### undefined (ウママニア)
undefined

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>near_count</span>~~==4@near_count==~~**&gt;=3&accumulatetime&gt;=**<span>5</span>~~@near_count==6@near_count==7~~</strong></div> <div>Duration: <strong><span>3</span></strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Trending in the Charts! (チャート急上昇！)
Increase velocity when engaged in a challenge mid-race. (Dirt)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>ground_type==2&phase==1&blocked_side_continuetime&gt;=2</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.35</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Top Pick (レコメンド)
Slightly increase velocity when engaged in a challenge mid-race. (Dirt)

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>ground_type==2&phase==1&blocked_side_continuetime&gt;=2</span></strong></div> <div>Duration: <strong>~~1.8~~ -&gt; **2.4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>speed</span>: <span>0.15</span></strong>(Target: <span>self</span>, max <span>1</span></span> )</div></div> </div></div>

---

### Burning Spirit WIT (アオハル燃焼・賢)
Burn bright with team spirit, increasing strategic navigation in proportion to the total Wit of racing team members early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==0</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.035</span></strong>(Target: <span>self</span>, max <span>1</span></span> <span>, scaled: <span>team_wisdom</span></span> )</div><div><span><strong><span>fov_up</span>: <span>15</span></strong>(Target: <span>self</span>, max <span>1</span></span> <span>, scaled: <span>team_wisdom</span></span> )</div></div> </div></div>

---

### Ignited Spirit WIT (アオハル点火・賢)
Burn bright with team spirit, slightly increasing strategic navigation in proportion to the total Wit of racing team members early-race.

**Changes:**

<div class="col-12 col-md-7"><div class="row"><div class="col"> <div>Condition: <strong><span>phase_random==0</span></strong></div> <div>Duration: <strong>~~3~~ -&gt; **4**</strong>// Cooldown:<strong><span>500</span></strong></div> <div><span><strong><span>lane_speed</span>: <span>0.015</span></strong>(Target: <span>self</span>, max <span>1</span></span> <span>, scaled: <span>team_wisdom</span></span> )</div><div><span><strong><span>fov_up</span>: <span>5</span></strong>(Target: <span>self</span>, max <span>1</span></span> <span>, scaled: <span>team_wisdom</span></span> )</div></div> </div></div>

---

