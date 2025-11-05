# Converted Skill Data

### Red Ace (レッドエース)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"><br>


Slightly swell with the determination to stay number one in the second half of the race.

 **Changes:** 

Condition: distance_rate>=50&order==1&bashin_diff_behind<=1 **@distance_rate>=50&order==2&is_overtake==1** 
Duration: 5
Cooldown:
500
speed: 0.15
(Target: self, max 1 )
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Added a new activation condition: now also works when you're in 2nd place (not just 1st) in the second half of the race, as long as you have someone to overtake. This makes the skill easier to trigger.

 **VI:** Thêm điều kiện kích hoạt mới: giờ cũng hoạt động khi bạn ở vị trí thứ 2 (không chỉ thứ nhất) trong nửa sau cuộc đua, miễn là bạn có người để vượt qua. Điều này giúp kỹ năng dễ kích hoạt hơn.

---

### Focused Mind (精神一到)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1011_101101.png" alt="char" width="50" height="50"><br>


Moderately increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

 **Changes:** 

Condition: is_finalcorner==1&corner==0&change_order_onetime<0&order>= ~~4~~  **3** 
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 4th or worse to 3rd or worse. Now activates when you're 3rd, 4th, 5th etc. on the final straight while overtaking someone. Easier to trigger.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 4 trở xuống sang thứ 3 trở xuống. Giờ kích hoạt khi bạn ở vị trí thứ 3, 4, 5... ở đường thẳng cuối khi đang vượt ai đó. Dễ kích hoạt hơn.

---

### Empress's Pride (エンプレス・プライド)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101801.png" alt="char" width="50" height="50"><br>


Moderately increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

 **Changes:** 

Condition: is_finalcorner==1&corner!=0&order>= ~~4~~  **3** &change_order_onetime<0
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 4th or worse to 3rd or worse. Now activates when you're 3rd, 4th, 5th etc. on a corner during final corner phase while overtaking. Easier to trigger.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 4 trở xuống sang thứ 3 trở xuống. Giờ kích hoạt khi bạn ở vị trí thứ 3, 4, 5... ở khúc cua trong giai đoạn khúc cua cuối khi đang vượt. Dễ kích hoạt hơn.

---

### 1st Place Kiss☆ (勝利のキッス☆)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102401.png" alt="char" width="50" height="50"><br>


Slightly increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

 **Changes:** 

Condition: is_finalcorner==1& ~~corner!=0&~~ blocked_side_continuetime>=2&order<=3
Duration: 5
Cooldown:
500
speed: 0.15
(Target: self, max 1 )
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed the requirement to be on a corner specifically (corner!=0). Now works on both the corner AND the final straight after the corner, as long as you're in top 3 and blocked from the side. More flexible.

 **VI:** Loại bỏ yêu cầu phải ở khúc cua cụ thể. Giờ hoạt động ở cả khúc cua VÀ đường thẳng cuối sau khúc cua, miễn là bạn ở top 3 và bị chặn từ bên hông. Linh hoạt hơn.

---

### Introduction to Physiology (introduction：My body)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20023.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1032_103201.png" alt="char" width="50" height="50"><br>


Moderately recover endurance when conserving energy on a corner in the second half of the race.

 **Changes:** 

Condition: distance_rate>=50&corner!=0&order>=3&order_rate<=40
Duration: ~~0~~ -> **4** 
Cooldown:
500
hp_recovery: 0.035
(Target: self, max 1 )
 **speed** : **0.15** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Duration increased from instant (0) to 4 seconds. Also now gives speed boost (0.15) on top of stamina recovery. Much stronger - you get stamina AND speed when saving energy on corners in second half.

 **VI:** Thời lượng tăng từ tức thì (0) lên 4 giây. Cũng tăng tốc độ (0.15) thêm vào việc hồi stamina. Mạnh hơn nhiều - bạn được cả stamina VÀ tốc độ khi tiết kiệm năng lượng ở khúc cua nửa sau.

---

### V Is for Victory! (全力Vサインッ！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>


Refuse to back down from a challenge, moderately increasing velocity on the final straight.

 **Changes:** 

Precondition: **is_finalcorner==1&blocked_side_continuetime>=2** 
Condition: is_finalcorner==1&corner==0&order<=5 ~~&blocked_side_continuetime>=2~~ 
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Moved the "blocked from side for 2+ seconds" condition from main condition to precondition. This makes activation more reliable - the blocking must happen on final corner, then skill activates on the straight after. More consistent timing.

 **VI:** Chuyển điều kiện "bị chặn từ bên trong 2+ giây" từ điều kiện chính sang điều kiện tiên quyết. Giúp kích hoạt đáng tin cậy hơn - phải bị chặn ở khúc cua cuối, sau đó kỹ năng kích hoạt ở đường thẳng. Thời điểm ổn định hơn.

---

### Clear Heart (クリアハート)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20023.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1045_104501.png" alt="char" width="50" height="50"><br>


Moderately recover endurance when well-positioned mid-race.

 **Changes:** 

Condition: phase_random==1&order>=2&order_rate<=40
Duration: 0
Cooldown:
500
hp_recovery: ~~0.035~~ -> **0.055** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Stamina recovery increased from 0.035 to 0.055 (57% increase). Recovers much more stamina when you're in top 40% position at a random point in mid-race.

 **VI:** Hồi phục stamina tăng từ 0.035 lên 0.055 (tăng 57%). Hồi nhiều stamina hơn khi bạn ở vị trí top 40% tại điểm ngẫu nhiên giữa cuộc đua.

---

### Luck Be with Me! (来てください来てください！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1056_105601.png" alt="char" width="50" height="50"><br>


Moderately clear a path forward with the power of divination when the way ahead is jammed late-race.

 **Changes:** 

Condition: phase>=2&order>=3&blocked_front==1
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.1) on top of existing speed boost. Now gives both speed AND acceleration when blocked from front in late-race phase while 3rd or worse. Better at breaking through traffic.

 **VI:** Thêm tăng gia tốc (0.1) vào tăng tốc độ hiện có. Giờ tăng cả tốc độ VÀ gia tốc khi bị chặn phía trước ở giai đoạn cuối khi đang ở vị trí thứ 3 trở xuống. Tốt hơn khi phá vòng vây.

---

### Call Me King (Call me KING)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1061_106101.png" alt="char" width="50" height="50"><br>


Increase velocity in a true display of skill with 200m remaining after racing calmly.

 **Changes:** 

Condition: temptation_count==0&remain_distance<=201&remain_distance>=199&order>= ~~5~~  **4** &order_rate<= ~~60~~  **70** 
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirements relaxed: now activates from 4th place (was 5th) and within top 70% of pack (was top 60%). Easier to activate at 200m mark when you haven't rushed during the race.

 **VI:** Yêu cầu vị trí nới lỏng: giờ kích hoạt từ vị trí thứ 4 (trước là 5) và trong top 70% (trước là top 60%). Dễ kích hoạt hơn ở mốc 200m khi bạn chưa lao nhanh trong cuộc đua.

---

### Shooting Star (シューティングスター)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100101.png" alt="char" width="50" height="50"><br>


Ride the momentum and increase velocity after passing another runner toward the front late-race.

 **Changes:** 

Condition: phase>=2&order>= ~~2~~  **1** &order_rate<=50&change_order_onetime<0
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Can now activate from 1st place (was 2nd+), and added acceleration boost (0.1). More flexible - works even when you're leading, as long as you're overtaking someone in top 50% of pack during late-race.

 **VI:** Giờ có thể kích hoạt từ vị trí thứ nhất (trước là từ thứ 2), và thêm tăng gia tốc (0.1). Linh hoạt hơn - hoạt động ngay cả khi bạn đang dẫn đầu, miễn là bạn đang vượt ai đó trong top 50% ở cuối cuộc đua.

---

### The View from the Lead Is Mine! (先頭の景色は譲らない…！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1002_100201.png" alt="char" width="50" height="50"><br>


Increase velocity by drawing on all remaining strength when in the lead by a fair margin on the final straight.

 **Changes:** 

Condition: ~~is_finalcorner==1~~  **distance_rate>=50** & ~~corner==0&~~ order==1&bashin_diff_behind>=1
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Completely changed activation timing. OLD: only on final straight/corner area. NEW: anytime in second half of race (50%+). No longer restricted to corners/straights - activates anywhere as long as you're 1st with 1+ horse length lead in second half. Activates much earlier now.

 **VI:** Thay đổi hoàn toàn thời điểm kích hoạt. CŨ: chỉ ở đường thẳng/khúc cua cuối. MỚI: bất cứ lúc nào trong nửa sau cuộc đua (50%+). Không còn giới hạn ở khúc cua/đường thẳng - kích hoạt ở bất cứ đâu miễn bạn thứ nhất và dẫn trước 1+ thân ngựa trong nửa sau. Kích hoạt sớm hơn nhiều.

---

### Lights of Vaudeville (煌星のヴォードヴィル)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1005_100501.png" alt="char" width="50" height="50"><br>


Greatly increase velocity with a dazzling display when just breaking out of the pack toward the front on the final straight.

 **Changes:** 

Condition: is_finalcorner==1&corner==0&order_rate<=30& ~~behind_near_lane_time~~  **behind_near_lane_time_set1** >=1
Duration: 5
Cooldown:
500
speed: 0.45
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed detection zone for horses behind you. OLD: 2.5m/1 lane. NEW: 5m/2.7 lanes (wider area). Easier to detect when someone's behind, making skill easier to activate when breaking out in top 30% on final straight.

 **VI:** Thay đổi vùng phát hiện ngựa phía sau bạn. CŨ: 2.5m/1 làn. MỚI: 5m/2.7 làn (khu vực rộng hơn). Dễ phát hiện khi có người ở phía sau, giúp kỹ năng dễ kích hoạt hơn khi thoát khỏi nhóm trong top 30% ở đường thẳng cuối.

---

### Resplendent Red Ace (ブリリアント・レッドエース)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"><br>


Swell with the determination to stay number one in the second half of the race.

 **Changes:** 

Condition: distance_rate>=50&order==1&bashin_diff_behind<=1 **@distance_rate>=50&order==2&is_overtake==1** 
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Added alternative activation condition: now also works when in 2nd place (not just 1st) in second half, as long as you have overtake target. Same as regular Red Ace but with stronger stats. More flexible.

 **VI:** Thêm điều kiện kích hoạt thay thế: giờ cũng hoạt động khi ở vị trí thứ 2 (không chỉ thứ nhất) trong nửa sau, miễn có mục tiêu vượt. Giống Red Ace thường nhưng chỉ số mạnh hơn. Linh hoạt hơn.

---

### Shooting for Victory! (ヴィクトリーショット！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20043.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"><br>


Increase acceleration with a pow, a wow, and a bang when well-positioned on the final corner.

 **Changes:** 

Condition: ~~is_finalcorner~~  **is_finalcorner_laterhalf** ==1&corner!=0&order>=3&order_rate<= ~~50~~  **40** 
Duration: 4
Cooldown:
500
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two changes: (1) Now only activates on second half of final corner (more precise timing). (2) Position requirement tightened from top 50% to top 40%. Activates at better timing but slightly harder to trigger.

 **VI:** Hai thay đổi: (1) Giờ chỉ kích hoạt ở nửa sau của khúc cua cuối (thời điểm chính xác hơn). (2) Yêu cầu vị trí thắt chặt từ top 50% xuống top 40%. Kích hoạt đúng thời điểm hơn nhưng hơi khó kích hoạt hơn chút.

---

### Where There's a Will, There's a Way (精神一到何事か成らざらん)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1011_101101.png" alt="char" width="50" height="50"><br>


Increase velocity with a strong turn of foot when passing another runner toward the back on the final straight.

 **Changes:** 

Condition: is_finalcorner==1&corner==0&change_order_onetime<0&order>= ~~4~~  **3** 
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 4th or worse to 3rd or worse. Stronger version of Focused Mind - same condition change, higher speed boost. Easier to trigger.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 4 trở xuống sang thứ 3 trở xuống. Phiên bản mạnh hơn của Focused Mind - cùng thay đổi điều kiện, tăng tốc độ cao hơn. Dễ kích hoạt hơn.

---

### You and Me! One-on-One! (タイマン！デッドヒート！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>


Increase velocity when passing another runner on the outside toward the back on the final straight.

 **Changes:** 

Precondition: **is_finalcorner==1&is_behind_in==1&change_order_onetime<0&order_rate>=40** 
Condition: is_finalcorner==1&corner==0 ~~&is_behind_in==1&change_order_onetime<0&order_rate>=40~~ 
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Moved complex conditions to precondition. Must be overtaking someone on outer lane in back half during final corner area first, then skill activates on the straight. Makes timing more predictable and reliable.

 **VI:** Chuyển các điều kiện phức tạp sang điều kiện tiên quyết. Phải vượt ai đó ở làn ngoài trong nửa sau tại khu vực khúc cua cuối trước, sau đó kỹ năng kích hoạt ở đường thẳng. Làm thời điểm dự đoán được và đáng tin cậy hơn.

---

### This Dance Is for Vittoria! (ヴィットーリアに捧ぐ舞踏)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"><br>


Increase velocity with royal brilliance when engaged in a challenge toward the front on the final corner.

 **Changes:** 

Condition: is_finalcorner==1& ~~corner!=0~~  **bashin_diff_behind<=1** & ~~bashin_diff_infront~~  **order** <= **4@is_finalcorner==** 1& ~~bashin_diff_behind~~  **bashin_diff_infront** <=1& ~~blocked_side_continuetime>=2&~~ order<=4
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Complete rework with 2 separate conditions: (1) Within 1 horse length behind someone while in top 4, OR (2) Within 1 horse length ahead of someone while in top 4. Removed blocking requirement. Focuses on close racing in top positions.

 **VI:** Làm lại hoàn toàn với 2 điều kiện riêng: (1) Trong vòng 1 thân ngựa phía sau ai đó khi ở top 4, HOẶC (2) Trong vòng 1 thân ngựa phía trước ai đó khi ở top 4. Loại bỏ yêu cầu bị chặn. Tập trung vào đua sát sao ở vị trí cao.

---

### Shadow Break (Shadow Break)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1016_101601.png" alt="char" width="50" height="50"><br>


Increase velocity with beastly strength when passing another runner on the outside on the final corner or later.

 **Changes:** 

Precondition: **phase==1&blocked_side_continuetime>=2** 
Condition: is_finalcorner==1&order>=2&order_rate<=75&is_behind_in==1&change_order_onetime<0
Duration: 5
Cooldown:
500
speed: ~~0.35~~ -> **0.45** 
(Target: self, max 1 )
Condition: **is_finalcorner==1&order>=2&order_rate<=75&is_behind_in==1&change_order_onetime<0** 
Duration: **5** 
Cooldown:
 **500** 
 **speed** : **0.35** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Now has TWO separate activations: (1) Added precondition variant - if blocked in mid-race, get 0.45 speed on final corner. (2) Normal activation stays at 0.35 speed. Can trigger twice in one race for massive boost when overtaking on outside.

 **VI:** Giờ có HAI lần kích hoạt riêng: (1) Thêm biến thể điều kiện tiên quyết - nếu bị chặn giữa cuộc đua, nhận 0.45 tốc độ ở khúc cua cuối. (2) Kích hoạt bình thường vẫn 0.35 tốc độ. Có thể kích hoạt 2 lần trong 1 cuộc đua để tăng khủng khi vượt bên ngoài.

---

### Blazing Pride (ブレイズ・オブ・プライド)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101801.png" alt="char" width="50" height="50"><br>


Increase velocity with the stride of an empress when passing another runner toward the back on the final corner.

 **Changes:** 

Condition: is_finalcorner==1&corner!=0&order>= ~~4~~  **3** &change_order_onetime<0
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 4th or worse to 3rd or worse. Stronger version of Empress's Pride - same condition change, higher speed boost. Easier to trigger.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 4 trở xuống sang thứ 3 trở xuống. Phiên bản mạnh hơn của Empress's Pride - cùng thay đổi điều kiện, tăng tốc độ cao hơn. Dễ kích hoạt hơn.

---

### undefined (尊み☆ﾗｽﾄｽﾊﾟ—(ﾟ∀ﾟ)—ﾄ!)
undefined

 **Changes:** 

Condition: change_order_up_end_after>=2
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )
 **lane_speed** : **0.035** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added navigation/lane speed boost (0.035) on top of existing speed boost. Activates after overtaking 2+ horses during late-race phase. Now gives both speed AND better lane movement.

 **VI:** Thêm tăng tốc di chuyển làn/điều hướng (0.035) vào tăng tốc độ hiện có. Kích hoạt sau khi vượt 2+ ngựa trong giai đoạn cuối. Giờ tăng cả tốc độ VÀ di chuyển làn tốt hơn.

---

### ∴win Q.E.D. (∴win Q.E.D.)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1023_102301.png" alt="char" width="50" height="50"><br>


Increase velocity by deriving the winning equation when passing another runner toward the front on the final corner.

 **Changes:** 

Condition: is_finalcorner==1& ~~corner!=0&~~ change_order_onetime<0&order<=4
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed corner requirement - now works on both corners AND final straight after final corner. More flexible activation timing while overtaking in top 4.

 **VI:** Loại bỏ yêu cầu phải ở khúc cua - giờ hoạt động ở cả khúc cua VÀ đường thẳng cuối sau khúc cua cuối. Thời điểm kích hoạt linh hoạt hơn khi vượt trong top 4.

---

### Flashy☆Landing (ひらめき☆ランディング)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102401.png" alt="char" width="50" height="50"><br>


Increase ability to break out of the pack on the straight after engaging in a challenge toward the front on the final corner.

 **Changes:** 

Condition: is_finalcorner==1& ~~corner!=0&~~ blocked_side_continuetime>=2&order<=3
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed corner requirement - now works on both corners AND final straight. Stronger version of 1st Place Kiss☆ with same condition change and better stats.

 **VI:** Loại bỏ yêu cầu phải ở khúc cua - giờ hoạt động ở cả khúc cua VÀ đường thẳng cuối. Phiên bản mạnh hơn của 1st Place Kiss☆ với cùng thay đổi điều kiện và chỉ số tốt hơn.

---

### Blue Rose Closer (ブルーローズチェイサー)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1030_103001.png" alt="char" width="50" height="50"><br>


Increase velocity with strong willpower when breaking out of the pack on the final straight.

 **Changes:** 

Precondition: **is_finalcorner==1&order<=4&change_order_onetime<0** 
Condition: is_finalcorner==1&corner==0 ~~&order<=4&change_order_onetime<0~~ 
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Moved overtaking conditions to precondition. Must be overtaking in top 4 during final corner area first, then activates on straight. More reliable and predictable timing.

 **VI:** Chuyển điều kiện vượt sang điều kiện tiên quyết. Phải vượt trong top 4 ở khu vực khúc cua cuối trước, sau đó kích hoạt ở đường thẳng. Thời điểm đáng tin cậy và dự đoán được hơn.

---

### U=ma2 (U=ma2)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20023.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1032_103201.png" alt="char" width="50" height="50"><br>


Recover endurance when conserving energy on a corner in the second half of the race.

 **Changes:** 

Condition: distance_rate>=50&corner!=0&order>=3&order_rate<=40
Duration: ~~0~~ -> **4** 
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )
 **speed** : **0.25** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Duration increased from instant (0) to 4 seconds. Added speed boost (0.25) on top of stamina recovery. Stronger version of Introduction to Physiology - more stamina recovery AND higher speed boost.

 **VI:** Thời lượng tăng từ tức thì (0) lên 4 giây. Thêm tăng tốc độ (0.25) vào hồi stamina. Phiên bản mạnh hơn của Introduction to Physiology - hồi stamina nhiều hơn VÀ tăng tốc độ cao hơn.

---

### Our Ticket to Win! (勝利のチケットを、君にッ！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>


Refuse to back down from a challenge, increasing velocity on the final straight.

 **Changes:** 

Precondition: **is_finalcorner==1&blocked_side_continuetime>=2** 
Condition: is_finalcorner==1&corner==0&order<=5 ~~&blocked_side_continuetime>=2~~ 
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Moved blocking condition to precondition. Stronger version of V Is for Victory! - same condition change with higher speed boost. More reliable activation.

 **VI:** Chuyển điều kiện bị chặn sang điều kiện tiên quyết. Phiên bản mạnh hơn của V Is for Victory! - cùng thay đổi điều kiện với tăng tốc độ cao hơn. Kích hoạt đáng tin cậy hơn.

---

### #LookatCurren (#LookatCurren)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1038_103801.png" alt="char" width="50" height="50"><br>


Gain momentum and begin to advance when passing another runner while well-positioned around halfway through the race.

 **Changes:** 

Condition: distance_rate>=50&distance_rate<=65&order>= ~~3~~  **2** &order_rate<=40&change_order_onetime<0
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 3rd or worse to 2nd or worse. Activates between 50-65% race progress. Can now trigger even when in 2nd place in top 40% while overtaking.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 3 trở xuống sang thứ 2 trở xuống. Kích hoạt giữa 50-65% tiến trình cuộc đua. Giờ có thể kích hoạt ngay cả khi ở vị trí thứ 2 trong top 40% khi đang vượt.

---

### undefined (姫たるもの、勝利をこの手に)
undefined

 **Changes:** 

Condition: is_finalcorner==1&corner==0& ~~order>=3&order_rate<=70&~~ blocked_side_continuetime>=2
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed position requirements completely - now only needs to be blocked from side for 2+ seconds on final straight. Can activate from any position, much easier to trigger.

 **VI:** Loại bỏ hoàn toàn yêu cầu vị trí - giờ chỉ cần bị chặn từ bên trong 2+ giây ở đường thẳng cuối. Có thể kích hoạt từ bất kỳ vị trí nào, dễ kích hoạt hơn nhiều.

---

### Pure Heart (ピュリティオブハート)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20023.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1045_104501.png" alt="char" width="50" height="50"><br>


Recover endurance when well-positioned mid-race.

 **Changes:** 

Condition: phase_random==1&order>=2&order_rate<=40
Duration: 0
Cooldown:
500
hp_recovery: ~~0.055~~ -> **0.075** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Stamina recovery increased from 0.055 to 0.075 (36% increase). Stronger version of Clear Heart - recovers even more stamina when in top 40% at random mid-race point.

 **VI:** Hồi phục stamina tăng từ 0.055 lên 0.075 (tăng 36%). Phiên bản mạnh hơn của Clear Heart - hồi nhiều stamina hơn nữa khi ở top 40% tại điểm ngẫu nhiên giữa cuộc đua.

---

### SPARKLY☆STARDOM (キラキラ☆STARDOM)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1046_104601.png" alt="char" width="50" height="50"><br>


Become empowered against ceding the spotlight when about to lose the lead on a straight mid-race.

 **Changes:** 

Condition: phase==1&corner==0&order ~~==1~~  **<=2** &bashin_diff_behind<=1
Duration: 5
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from only 1st place to top 2. Now activates when 1st OR 2nd on straights in mid-race with close competition behind. Easier to trigger.

 **VI:** Yêu cầu vị trí nới lỏng từ chỉ vị trí thứ nhất sang top 2. Giờ kích hoạt khi thứ nhất HOẶC thứ 2 ở đường thẳng giữa cuộc đua với đối thủ đeo bám phía sau. Dễ kích hoạt hơn.

---

### Nemesis (Nemesis)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1050_105001.png" alt="char" width="50" height="50"><br>


Increase velocity with smoldering ambition when moving up from a position toward the back of the pack on the final corner.

 **Changes:** 

Condition: is_finalcorner==1& ~~corner!=0&~~ order_rate>= ~~50~~  **40** &order_rate<=75&is_overtake==1
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two changes: (1) Removed corner requirement - works on corners AND straight. (2) Position range changed from 50-75% to 40-75%. Activates when overtaking from middle positions during final corner phase.

 **VI:** Hai thay đổi: (1) Loại bỏ yêu cầu khúc cua - hoạt động ở khúc cua VÀ đường thẳng. (2) Phạm vi vị trí thay đổi từ 50-75% sang 40-75%. Kích hoạt khi vượt từ vị trí giữa trong giai đoạn khúc cua cuối.

---

### I See Victory in My Future! (来ます来てます来させます！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1056_105601.png" alt="char" width="50" height="50"><br>


Clear a path forward with the power of divination when the way ahead is jammed late-race.

 **Changes:** 

Condition: phase>=2&order>=3&blocked_front==1
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.1) on top of speed boost. Stronger version of Luck Be with Me! - same conditions with higher speed. Better at breaking through when blocked.

 **VI:** Thêm tăng gia tốc (0.1) vào tăng tốc độ. Phiên bản mạnh hơn của Luck Be with Me! - cùng điều kiện với tốc độ cao hơn. Tốt hơn khi phá vòng vây khi bị chặn.

---

### Prideful King (Pride of KING)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1061_106101.png" alt="char" width="50" height="50"><br>


Greatly increase velocity in a true display of skill with 200m remaining after racing calmly.

 **Changes:** 

Condition: temptation_count==0&remain_distance<=201&remain_distance>=199&order>= ~~5~~  **4** &order_rate<= ~~60~~  **70** 
Duration: 5
Cooldown:
500
speed: 0.45
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirements relaxed from 5th+ to 4th+, and top 60% to top 70%. Stronger version of Call Me King - same condition changes with higher speed boost. Easier to trigger at 200m mark.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ 5+ sang thứ 4+, và top 60% sang top 70%. Phiên bản mạnh hơn của Call Me King - cùng thay đổi điều kiện với tăng tốc độ cao hơn. Dễ kích hoạt hơn ở mốc 200m.

---

### Certain Victory (絶対は、ボクだ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100302.png" alt="char" width="50" height="50"><br>


Increase velocity with an indomitable fighting spirit when on the heels of another runner toward the front on the final straight.

 **Changes:** 

Precondition: **is_finalcorner==1&is_overtake==1&order<=5&order_rate<=50&overtake_target_no_order_up_time>=2** 
Condition: is_finalcorner==1&corner==0 ~~&is_overtake==1&order<=5&order_rate<=50&overtake_target_no_order_up_time>=2~~ 
Duration: 5
Cooldown:
500
speed: ~~0.35~~ -> **0.45** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two changes: (1) Moved complex conditions to precondition for reliable timing. (2) Speed increased from 0.35 to 0.45. Must chase overtake target for 2+ seconds on final corner, then big boost on straight.

 **VI:** Hai thay đổi: (1) Chuyển điều kiện phức tạp sang điều kiện tiên quyết để thời điểm ổn định. (2) Tốc độ tăng từ 0.35 lên 0.45. Phải đuổi mục tiêu vượt trong 2+ giây ở khúc cua cuối, sau đó tăng mạnh ở đường thẳng.

---

### Superior Heal (ゲインヒール・スペリアー)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20023.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1011_101102.png" alt="char" width="50" height="50"><br>


Recover endurance with a gentle light when dropping down toward the back mid-race.

 **Changes:** 

Condition: phase==1&change_order_onetime>0&order_rate>=40
Duration: 0
Cooldown:
500
hp_recovery: ~~0.055~~ -> **0.075** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Stamina recovery increased from 0.055 to 0.075 (36% increase). Recovers more stamina when getting overtaken and dropping to back 60% positions in mid-race.

 **VI:** Hồi phục stamina tăng từ 0.055 lên 0.075 (tăng 36%). Hồi nhiều stamina hơn khi bị vượt và rơi xuống vị trí 60% cuối giữa cuộc đua.

---

### Legacy of the Strong (最強の名を懸けて)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101302.png" alt="char" width="50" height="50"><br>


Increase velocity when pressured by another runner and running out of energy toward the front on the final corner or later.

 **Changes:** 

Condition: is_finalcorner==1&hp_per<= ~~35~~  **45** &order<=3&order_rate<=50&bashin_diff_behind<=1&overtake_target_time>=1
Duration: ~~5~~ -> **6** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two buffs: (1) HP threshold increased from 35% to 45% - triggers earlier when running low on stamina. (2) Duration increased from 5 to 6 seconds. Activates when in top 3 with close competition and low stamina.

 **VI:** Hai cải thiện: (1) Ngưỡng HP tăng từ 35% lên 45% - kích hoạt sớm hơn khi sắp hết stamina. (2) Thời lượng tăng từ 5 lên 6 giây. Kích hoạt khi ở top 3 với đối thủ đeo bám và stamina thấp.

---

### Eternal Moments (薫風、永遠なる瞬間を)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20013.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101802.png" alt="char" width="50" height="50"><br>


Increase velocity when starting to make a move from a position toward the front mid-race.

 **Changes:** 

Condition: ~~phase_random~~  **phase** ==1&order>=3&order_rate<=50&is_overtake==1
Duration: 5
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from random point to entire mid-race phase. OLD: activates at one random moment. NEW: can activate anytime during whole mid-race when overtaking from top 50% while 3rd+. More activation opportunities.

 **VI:** Thay đổi từ điểm ngẫu nhiên sang toàn bộ giai đoạn giữa cuộc đua. CŨ: kích hoạt tại một thời điểm ngẫu nhiên. MỚI: có thể kích hoạt bất cứ lúc nào trong suốt giữa cuộc đua khi vượt từ top 50% khi ở vị trí thứ 3+. Nhiều cơ hội kích hoạt hơn.

---

### undefined (Drain for rose)
undefined

 **Changes:** 

Condition: phase==1& ~~distance_rate>=50&~~ order>=2&order_rate<=50&overtake_target_time>=1
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )
hp_recovery: -0.005
(Target: ahead, max 18 )

 **What Changed:** 

 **EN:** Removed 50%+ race progress requirement. Now activates throughout entire mid-race phase (not just second half). Can drain stamina from opponents earlier. More activation opportunities.

 **VI:** Loại bỏ yêu cầu tiến trình 50%+ cuộc đua. Giờ kích hoạt trong suốt toàn bộ giai đoạn giữa cuộc đua (không chỉ nửa sau). Có thể hút stamina từ đối thủ sớm hơn. Nhiều cơ hội kích hoạt hơn.

---

### Maverick ◎ (おひとり様◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_10011.png" alt="icon" width="50" height="50">



Increase performance when no other runners are using the same strategy.

 **Changes:** 

Condition: running_style_count_same<=1
Duration: -0.0001
Cooldown:
0
speed_stat_up: ~~60~~ -> **80** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Speed stat bonus increased from 60 to 80 (33% increase). This is a passive boost that lasts entire race when you're the only one using your running style (e.g., only Front Runner).

 **VI:** Tăng chỉ số tốc độ từ 60 lên 80 (tăng 33%). Đây là tăng buff thụ động kéo dài cả cuộc đua khi bạn là người duy nhất dùng phong cách chạy của mình (vd: Front Runner duy nhất).

---

### Maverick ○ (おひとり様○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_10011.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10015.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30046.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30057.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20021.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20023.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10022.png" alt="support event" width="50" height="50"><br>


Moderately increase performance when no other runners are using the same strategy.

 **Changes:** 

Condition: running_style_count_same<=1
Duration: -0.0001
Cooldown:
0
speed_stat_up: ~~40~~ -> **60** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Speed stat bonus increased from 40 to 60 (50% increase). Weaker version of Maverick ◎ but still significant buff when running unique style.

 **VI:** Tăng chỉ số tốc độ từ 40 lên 60 (tăng 50%). Phiên bản yếu hơn của Maverick ◎ nhưng vẫn là buff đáng kể khi chạy phong cách độc nhất.

---

### Competitive Spirit ◎ (対抗意識◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_10031.png" alt="icon" width="50" height="50">



Increase performance when at least 5 other runners are using the same strategy.

 **Changes:** 

Condition: ~~running_style_count_same~~  **running_style_count_same_rate** >= ~~6~~  **40** 
Duration: -0.0001
Cooldown:
0
power_stat_up: 60
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from counting horses (6+) to percentage (40%+). More flexible - works in races with different field sizes. Now based on 40% of field sharing your style instead of exact count of 6.

 **VI:** Thay đổi từ đếm ngựa (6+) sang phần trăm (40%+). Linh hoạt hơn - hoạt động trong các cuộc đua với số lượng đối thủ khác nhau. Giờ dựa trên 40% đàn chia sẻ phong cách của bạn thay vì số lượng chính xác là 6.

---

### Competitive Spirit ○ (対抗意識○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_10031.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30006.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20031.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10051.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10066.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30042.png" alt="support event" width="50" height="50"><br>


Moderately increase performance when at least 5 other runners are using the same strategy.

 **Changes:** 

Condition: ~~running_style_count_same~~  **running_style_count_same_rate** >= ~~6~~  **40** 
Duration: -0.0001
Cooldown:
0
power_stat_up: 40
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from counting horses (6+) to percentage (40%+). Weaker version of Competitive Spirit ◎ with same condition change. More flexible across different field sizes.

 **VI:** Thay đổi từ đếm ngựa (6+) sang phần trăm (40%+). Phiên bản yếu hơn của Competitive Spirit ◎ với cùng thay đổi điều kiện. Linh hoạt hơn với các kích thước đàn khác nhau.

---

### Wallflower (引っ込み思案)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_10034.png" alt="icon" width="50" height="50">



Moderately decrease performance when at least 5 other runners are using the same strategy.

 **Changes:** 

Condition: ~~running_style_count_same~~  **running_style_count_same_rate** >= ~~6~~  **40** 
Duration: -0.0001
Cooldown:
0
power_stat_up: -40
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from counting horses (6+) to percentage (40%+). This is a DEBUFF skill - same condition change as Competitive Spirit but hurts instead of helps. Avoid if possible.

 **VI:** Thay đổi từ đếm ngựa (6+) sang phần trăm (40%+). Đây là kỹ năng DEBUFF - cùng thay đổi điều kiện như Competitive Spirit nhưng gây hại thay vì giúp đỡ. Tránh nếu có thể.

---

### Professor of Curvature (弧線のプロフェッサー)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1017_101701.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support event" width="50" height="50"><br>


Increase velocity on a corner with skilled turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
30
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two changes: (1) Simplified activation - now picks 4 random corner points instead of 4 separate conditions. (2) Duration increased from 1.8 to 2.4 seconds. Lasts longer on corners.

 **VI:** Hai thay đổi: (1) Kích hoạt đơn giản hơn - giờ chọn 4 điểm khúc cua ngẫu nhiên thay vì 4 điều kiện riêng. (2) Thời lượng tăng từ 1.8 lên 2.4 giây. Kéo dài hơn ở khúc cua.

---

### Corner Adept ○ (コーナー巧者○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1017_101701.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102402.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10030.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10055.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30010.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10028.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity on a corner with skilled turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
30
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation and duration increased from 1.8 to 2.4 seconds. Weaker version of Professor of Curvature with same changes.

 **VI:** Kích hoạt đơn giản hơn và thời lượng tăng từ 1.8 lên 2.4 giây. Phiên bản yếu hơn của Professor of Curvature với cùng thay đổi.

---

### Corner Adept × (コーナー巧者×)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20014.png" alt="icon" width="50" height="50">



Moderately decrease velocity on a corner with clumsy turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
30
current_speed: -0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** DEBUFF skill - same changes as corner skills above but SLOWS you down. Duration increased means you're slowed for longer (2.4s instead of 1.8s). Avoid this skill!

 **VI:** Kỹ năng DEBUFF - cùng thay đổi như các kỹ năng khúc cua trên nhưng LÀM CHẬM bạn. Thời lượng tăng nghĩa là bạn bị chậm lâu hơn (2.4s thay vì 1.8s). Tránh kỹ năng này!

---

### Corner Connoisseur (曲線のソムリエ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1006_100601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101802.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30004.png" alt="support event" width="50" height="50"><br>


Increase acceleration on a corner with masterful turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **3** 
Cooldown:
30
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation and duration increased from 1.8 to 3 seconds. Acceleration version of corner skills - lasts even longer than speed variants.

 **VI:** Kích hoạt đơn giản hơn và thời lượng tăng từ 1.8 lên 3 giây. Phiên bản gia tốc của kỹ năng khúc cua - kéo dài lâu hơn cả biến thể tốc độ.

---

### Corner Acceleration ○ (コーナー加速○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1006_100601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101802.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30054.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20019.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10047.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30031.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20011.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10034.png" alt="support event" width="50" height="50"><br>


Slightly increase acceleration on a corner with masterful turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **3** 
Cooldown:
30
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation and duration increased from 1.8 to 3 seconds. Weaker version of Corner Connoisseur with same changes.

 **VI:** Kích hoạt đơn giản hơn và thời lượng tăng từ 1.8 lên 3 giây. Phiên bản yếu hơn của Corner Connoisseur với cùng thay đổi.

---

### Corner Acceleration × (コーナー加速×)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20044.png" alt="icon" width="50" height="50">



Moderately decrease acceleration on a corner with awkward turning.

 **Changes:** 

Condition: ~~corner_random~~  **all_corner_random** ==1 ~~@corner_random==2@corner_random==3@corner_random==4~~ 
Duration: ~~1.8~~ -> **3** 
Cooldown:
30
acceleration: -0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** DEBUFF skill - reduces acceleration on corners. Duration increased from 1.8 to 3 seconds means you struggle to speed up for longer. Avoid this skill!

 **VI:** Kỹ năng DEBUFF - giảm gia tốc ở khúc cua. Thời lượng tăng từ 1.8 lên 3 giây nghĩa là bạn khó tăng tốc lâu hơn. Tránh kỹ năng này!

---

### Beeline Burst (ハヤテ一文字)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101302.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1016_101601.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30018.png" alt="support event" width="50" height="50"><br>


Increase velocity on a straight.

 **Changes:** 

Condition: straight_random==1
Duration: ~~0.9~~ -> **2.4** 
Cooldown:
30
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration massively increased from 0.9 to 2.4 seconds (167% increase). Speed boost now lasts much longer on straights. Major buff.

 **VI:** Thời lượng tăng khủng từ 0.9 lên 2.4 giây (tăng 167%). Tăng tốc độ giờ kéo dài lâu hơn nhiều ở đường thẳng. Buff lớn.

---

### Straightaway Adept (直線巧者)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101302.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1016_101601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1014_101401.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20015.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10030.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10043.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10059.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10065.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30018.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20007.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20027.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10030.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity on a straight.

 **Changes:** 

Condition: straight_random==1
Duration: ~~0.9~~ -> **2.4** 
Cooldown:
30
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 0.9 to 2.4 seconds (167% increase). Weaker version of Beeline Burst with same duration buff.

 **VI:** Thời lượng tăng từ 0.9 lên 2.4 giây (tăng 167%). Phiên bản yếu hơn của Beeline Burst với cùng buff thời lượng.

---

### Rushing Gale! (一陣の風)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30003.png" alt="support event" width="50" height="50"><br>


Increase acceleration on a straight.

 **Changes:** 

Condition: straight_random==1
Duration: ~~1.8~~ -> **3** 
Cooldown:
30
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds (67% increase). Acceleration boost lasts longer on straights.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây (tăng 67%). Tăng gia tốc kéo dài lâu hơn ở đường thẳng.

---

### Straightaway Acceleration (直線加速)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1008_100801.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30010.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20013.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10038.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20004.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20027.png" alt="support event" width="50" height="50"><br>


Slightly increase acceleration on a straight.

 **Changes:** 

Condition: straight_random==1
Duration: ~~1.8~~ -> **3** 
Cooldown:
30
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds. Weaker version of Rushing Gale! with same duration buff.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây. Phiên bản yếu hơn của Rushing Gale! với cùng buff thời lượng.

---

### Ramp Revulsion (坂苦手)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20024.png" alt="icon" width="50" height="50">



Moderately increase fatigue on an uphill.

 **Changes:** 

Condition: ~~slope~~  **up_slope_random** ==1
Duration: 0
Cooldown:
500
hp_recovery: -0.02
(Target: self, max 1 )

 **What Changed:** 

 **EN:** DEBUFF skill - Changed to more specific uphill detection. Now triggers at random uphill points. Still drains stamina on uphills - avoid this skill!

 **VI:** Kỹ năng DEBUFF - Thay đổi sang phát hiện dốc lên cụ thể hơn. Giờ kích hoạt tại các điểm dốc lên ngẫu nhiên. Vẫn hút stamina ở dốc lên - tránh kỹ năng này!

---

### Packphobia (バ群嫌い)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20024.png" alt="icon" width="50" height="50">



Moderately lose endurance when surrounded.

 **Changes:** 

Condition: accumulatetime>=2& ~~blocked_all_continuetime>=~~  **is_surrounded==** 1
Duration: 0
Cooldown:
500
hp_recovery: -0.02
(Target: self, max 1 )

 **What Changed:** 

 **EN:** DEBUFF skill - Changed to clearer surrounded detection. Uses new is_surrounded check (front+back+side blocked). Still drains stamina when boxed in - avoid this skill!

 **VI:** Kỹ năng DEBUFF - Thay đổi sang phát hiện bị vây rõ ràng hơn. Dùng kiểm tra is_surrounded mới (bị chặn trước+sau+bên). Vẫn hút stamina khi bị vây - tránh kỹ năng này!

---

### Defeatist (あきらめ癖)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20014.png" alt="icon" width="50" height="50">



Moderately increase urge to give up when positioned around the very back on the final straight.

 **Changes:** 

Condition: ~~is_finalcorner~~  **last_straight_random** ==1& ~~is_lastspurt==1&straight_random==1&corner==0&~~ distance_diff_rate>=75
Duration: 3
Cooldown:
30
current_speed: -0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** DEBUFF skill - Simplified to just trigger at random point on last straight. Removed position requirements. May trigger more often now - definitely avoid this skill!

 **VI:** Kỹ năng DEBUFF - Đơn giản hóa chỉ kích hoạt tại điểm ngẫu nhiên ở đường thẳng cuối. Loại bỏ yêu cầu vị trí. Có thể kích hoạt thường xuyên hơn - chắc chắn tránh kỹ năng này!

---

### Iron Will (鋼の意志)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1052_105201.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30029.png" alt="support event" width="50" height="50"><br>


Recover endurance when the way ahead is jammed early-race.

 **Changes:** 

Condition: phase ~~==0~~  **<=1** &accumulatetime>=5&blocked_front_continuetime>=1
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Phase expanded from only Early-Race to Early+Mid-Race (phase 0 and 1). Can now recover stamina when blocked in both early phases instead of just early. More activation opportunities.

 **VI:** Giai đoạn mở rộng từ chỉ Đầu cuộc đua sang Đầu+Giữa cuộc đua (giai đoạn 0 và 1). Giờ có thể hồi stamina khi bị chặn ở cả hai giai đoạn đầu thay vì chỉ đầu. Nhiều cơ hội kích hoạt hơn.

---

### Lay Low (隠れ蓑)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1052_105201.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30030.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30054.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20019.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20025.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10040.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10053.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10057.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20021.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10022.png" alt="support event" width="50" height="50"><br>


Slightly recover endurance when the way ahead is jammed early-race.

 **Changes:** 

Condition: phase ~~==0~~  **<=1** &accumulatetime>=5&blocked_front_continuetime>=1
Duration: 0
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Phase expanded from only Early-Race to Early+Mid-Race. Weaker version of Iron Will with same phase expansion.

 **VI:** Giai đoạn mở rộng từ chỉ Đầu cuộc đua sang Đầu+Giữa cuộc đua. Phiên bản yếu hơn của Iron Will với cùng mở rộng giai đoạn.

---

### Center Stage (注目の踊り子)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20052.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1046_104601.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30017.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30039.png" alt="support event" width="50" height="50"><br>


Increase navigation early-race.

 **Changes:** 

Condition: phase_random==0
Duration: 3
Cooldown:
500
lane_speed: ~~0.035~~ -> **0.045** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Lane speed (navigation) increased from 0.035 to 0.045 (29% increase). Better at positioning and avoiding traffic at random point in early-race.

 **VI:** Tốc độ làn (điều hướng) tăng từ 0.035 lên 0.045 (tăng 29%). Tốt hơn ở việc định vị và tránh vòng vây tại điểm ngẫu nhiên đầu cuộc đua.

---

### Prudent Positioning (ポジションセンス)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20051.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100302.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1046_104601.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30045.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10050.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10059.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30017.png" alt="support event" width="50" height="50"><br>


Moderately increase navigation early-race.

 **Changes:** 

Condition: phase_random==0
Duration: 3
Cooldown:
500
lane_speed: ~~0.025~~ -> **0.035** 
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Lane speed increased from 0.025 to 0.035 (40% increase). Weaker version of Center Stage with same percentage buff.

 **VI:** Tốc độ làn tăng từ 0.025 lên 0.035 (tăng 40%). Phiên bản yếu hơn của Center Stage với cùng phần trăm buff.

---

### Unruffled (どこ吹く風)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30019.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30030.png" alt="support event" width="50" height="50"><br>


Recover endurance when surrounded mid-race.

 **Changes:** 

Condition: phase==1& ~~blocked_all_continuetime>=~~  **is_surrounded==** 1
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed to clearer surrounded detection using is_surrounded check. Activates in mid-race when boxed in by other horses (front+back+side).

 **VI:** Thay đổi sang phát hiện bị vây rõ ràng hơn dùng kiểm tra is_surrounded. Kích hoạt giữa cuộc đua khi bị vây bởi ngựa khác (trước+sau+bên).

---

### Calm in a Crowd (ウマ込み冷静)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20016.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20025.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10040.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10044.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10053.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30009.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30030.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10027.png" alt="support event" width="50" height="50"><br>


Slightly recover endurance when surrounded mid-race.

 **Changes:** 

Condition: phase==1& ~~blocked_all_continuetime>=~~  **is_surrounded==** 1
Duration: 0
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed to clearer surrounded detection. Weaker version of Unruffled with same condition change.

 **VI:** Thay đổi sang phát hiện bị vây rõ ràng hơn. Phiên bản yếu hơn của Unruffled với cùng thay đổi điều kiện.

---

### No Stopping Me! (ノンストップガール)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102401.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30031.png" alt="support event" width="50" height="50"><br>


Increase maneuverability when the way ahead is blocked in the last spurt.

 **Changes:** 

Condition: ~~blocked_front_continuetime~~  **infront_near_lane_time** >=1&is_lastspurt==1&hp_per>=1
Duration: 3
Cooldown:
30
acceleration: 0.4
(Target: self, max 1 )
lane_speed: 0.025
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed to more precise front detection - now checks for horses directly in front (within 2.5m/1 lane) instead of just general blocking. Better at detecting when you need to navigate around slower horses.

 **VI:** Thay đổi sang phát hiện phía trước chính xác hơn - giờ kiểm tra ngựa ngay phía trước (trong 2.5m/1 làn) thay vì chỉ chặn chung. Tốt hơn ở phát hiện khi cần điều hướng quanh ngựa chậm hơn.

---

### Nimble Navigator (垂れウマ回避)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1006_100601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102401.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30010.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10030.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10059.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30005.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20010.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10007.png" alt="support event" width="50" height="50"><br>


Slightly increase maneuverability when the way ahead is blocked in the last spurt.

 **Changes:** 

Condition: ~~blocked_front_continuetime~~  **infront_near_lane_time** >=1&is_lastspurt==1&hp_per>=1
Duration: 3
Cooldown:
30
acceleration: 0.2
(Target: self, max 1 )
lane_speed: 0.005
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed to more precise front detection. Weaker version of No Stopping Me! with same condition change.

 **VI:** Thay đổi sang phát hiện phía trước chính xác hơn. Phiên bản yếu hơn của No Stopping Me! với cùng thay đổi điều kiện.

---

### In Body and Mind (全身全霊)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100101.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1016_101601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1037_103701.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30001.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30033.png" alt="support event" width="50" height="50"><br>


Increase velocity in the last spurt.

 **Changes:** 

Condition: is_lastspurt==1&phase_random==3
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds (33% increase). Speed boost lasts longer during last spurt phase.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây (tăng 33%). Tăng tốc độ kéo dài lâu hơn trong giai đoạn cố cuối.

---

### Homestretch Haste (末脚)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100101.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1014_101402.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1016_101601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1037_103701.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1011_101101.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30001.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30006.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30016.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30025.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30032.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10001.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10019.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10058.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30001.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30042.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30056.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20013.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20020.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10048.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity in the last spurt.

 **Changes:** 

Condition: is_lastspurt==1&phase_random==3
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds. Weaker version of In Body and Mind with same duration buff.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây. Phiên bản yếu hơn của In Body and Mind với cùng buff thời lượng.

---

### Taking the Lead (先手必勝)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1026_102601.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support event" width="50" height="50"><br>


Increase ability to go to the front early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase==0 ~~&accumulatetime>=5~~ 
Duration: 1.2
Cooldown:
500
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed 5 second wait requirement. Now activates immediately at race start for Front Runners. Can boost to the front faster from the gate.

 **VI:** Loại bỏ yêu cầu chờ 5 giây. Giờ kích hoạt ngay lập tức khi bắt đầu cuộc đua cho Front Runner. Có thể tăng tốc lên đầu nhanh hơn từ cổng xuất phát.

---

### Early Lead (先駆け)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1026_102601.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30027.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10032.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10051.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10054.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10010.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10051.png" alt="support event" width="50" height="50"><br>


Slightly increase ability to go to the front early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase==0 ~~&accumulatetime>=5~~ 
Duration: 1.2
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Removed 5 second wait requirement. Weaker version of Taking the Lead with same timing improvement.

 **VI:** Loại bỏ yêu cầu chờ 5 giây. Phiên bản yếu hơn của Taking the Lead với cùng cải thiện thời điểm.

---

### Calm and Collected (余裕綽々)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1023_102301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1014_101401.png" alt="char" width="50" height="50"><br>


Decrease fatigue early-race. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~phase_random~~  **phase_laterhalf_random** ==0& ~~accumulatetime>=5&~~ order_rate<=50
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two changes: (1) Changed from random point to second half of early-race phase. (2) Removed time and position requirements. Activates more reliably for Pace Chasers in latter part of early phase.

 **VI:** Hai thay đổi: (1) Thay đổi từ điểm ngẫu nhiên sang nửa sau của giai đoạn đầu. (2) Loại bỏ yêu cầu thời gian và vị trí. Kích hoạt đáng tin cậy hơn cho Pace Chaser trong phần sau của giai đoạn đầu.

---

### Stamina to Spare (スタミナキープ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101302.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1023_102301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1014_101401.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20035.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10010.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10052.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10070.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30007.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support event" width="50" height="50"><br>


Slightly decrease fatigue early-race. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~phase_random~~  **phase_laterhalf_random** ==0& ~~accumulatetime>=5&~~ order_rate<=50
Duration: 0
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed timing and removed requirements. Weaker version of Calm and Collected with same changes.

 **VI:** Thay đổi thời điểm và loại bỏ yêu cầu. Phiên bản yếu hơn của Calm and Collected với cùng thay đổi.

---

### Speed Star (スピードスター)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1058_105801.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30010.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30038.png" alt="support event" width="50" height="50"><br>


Increase ability to break out of the pack on the final corner. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&is_finalcorner_random==1&order_rate<=50
Duration: ~~1.2~~ -> **1.8** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.2 to 1.8 seconds (50% increase). Speed boost lasts longer when breaking out on final corner for Pace Chasers in top 50%.

 **VI:** Thời lượng tăng từ 1.2 lên 1.8 giây (tăng 50%). Tăng tốc độ kéo dài lâu hơn khi thoát ra ở khúc cua cuối cho Pace Chaser trong top 50%.

---

### Prepared to Pass (抜け出し準備)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1038_103801.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1058_105801.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30032.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20031.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10008.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10058.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10066.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30010.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30038.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20001.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20017.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10008.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10049.png" alt="support event" width="50" height="50"><br>


Slightly increase ability to break out of the pack on the final corner. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&is_finalcorner_random==1&order_rate<=50
Duration: ~~1.2~~ -> **1.8** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.2 to 1.8 seconds. Weaker version of Speed Star with same duration buff.

 **VI:** Thời lượng tăng từ 1.2 lên 1.8 giây. Phiên bản yếu hơn của Speed Star với cùng buff thời lượng.

---

### Fast & Furious (迅速果断)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100102.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30009.png" alt="support event" width="50" height="50"><br>


Increase velocity mid-race. (Late Surger)

 **Changes:** 

Condition: running_style==3&phase_random==1&order_rate>50
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds (33% increase). Speed boost lasts longer for Late Surgers in back half of pack during mid-race.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây (tăng 33%). Tăng tốc độ kéo dài lâu hơn cho Late Surger ở nửa sau đàn trong giữa cuộc đua.

---

### Position Pilfer (位置取り押し上げ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100102.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1011_101101.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30006.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30033.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30046.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20035.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10016.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10070.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity mid-race. (Late Surger)

 **Changes:** 

Condition: running_style==3&phase_random==1&order_rate>50
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds. Weaker version of Fast & Furious with same duration buff.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây. Phiên bản yếu hơn của Fast & Furious với cùng buff thời lượng.

---

### Sturm und Drang (疾風怒濤)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>


Move up in preparation to close the gap late-race. (End Closer)

 **Changes:** 

Condition: running_style==4&phase_random==2&distance_diff_rate>= ~~75~~  **50** 
Duration: 3
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Distance gap requirement relaxed from 75% to 50%. Now activates when further behind - easier for End Closers to trigger when positioning to make their late move.

 **VI:** Yêu cầu khoảng cách nới lỏng từ 75% xuống 50%. Giờ kích hoạt khi ở xa phía sau hơn - dễ hơn cho End Closer kích hoạt khi định vị để thực hiện động thái cuối.

---

### Masterful Gambit (仕掛け抜群)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10040.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20003.png" alt="support event" width="50" height="50"><br>


Slightly move up in preparation to close the gap late-race. (End Closer)

 **Changes:** 

Condition: running_style==4&phase_random==2&distance_diff_rate>= ~~75~~  **50** 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Distance gap relaxed from 75% to 50%. Weaker version of Sturm und Drang with same condition change.

 **VI:** Khoảng cách nới lỏng từ 75% xuống 50%. Phiên bản yếu hơn của Sturm und Drang với cùng thay đổi điều kiện.

---

### Wait-and-See (様子見)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30056.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10048.png" alt="support hint" width="50" height="50"><br>


Slightly decrease fatigue when positioned toward the back mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==1&order_rate>50
Duration: ~~0~~ -> **3** 
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Two buffs: (1) Duration increased from instant (0) to 3 seconds. (2) Added acceleration boost (0.1). For Sprint distance, now gives stamina recovery AND acceleration when in back half mid-race.

 **VI:** Hai buff: (1) Thời lượng tăng từ tức thì (0) lên 3 giây. (2) Thêm tăng gia tốc (0.1). Với cự ly Sprint, giờ hồi stamina VÀ tăng gia tốc khi ở nửa sau giữa cuộc đua.

---

### Blinding Flash (電撃の煌めき)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1061_106101.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30056.png" alt="support event" width="50" height="50"><br>


Increase spurting ability when positioned toward the back late-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==2&order_rate>50
Duration: 3
Cooldown:
500
speed: 0.35
(Target: self, max 1 )
 **acceleration** : **0.2** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.2) on top of speed. For Sprint distance, now gives both speed AND acceleration when in back half during late-race.

 **VI:** Thêm tăng gia tốc (0.2) vào tốc độ. Với cự ly Sprint, giờ tăng cả tốc độ VÀ gia tốc khi ở nửa sau trong cuối cuộc đua.

---

### Gap Closer (詰め寄り)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1061_106101.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30056.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10048.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10065.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30015.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30056.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10018.png" alt="support event" width="50" height="50"><br>


Slightly increase spurting ability when positioned toward the back late-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==2&order_rate>50
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )
 **acceleration** : **0.05** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.05). Weaker version of Blinding Flash - also gets acceleration buff but with lower values.

 **VI:** Thêm tăng gia tốc (0.05). Phiên bản yếu hơn của Blinding Flash - cũng được buff gia tốc nhưng giá trị thấp hơn.

---

### Mile Maven (マイルの支配者)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100402.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"><br>


Widen the margin when in the lead early-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==0&accumulatetime>=5& ~~order==1~~  **order_rate<=50** 
Duration: 3
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from only 1st place to top 50% of pack. For Mile distance, now activates when in front half instead of only when leading.

 **VI:** Yêu cầu vị trí nới lỏng từ chỉ vị trí thứ nhất sang top 50% đàn. Với cự ly Mile, giờ kích hoạt khi ở nửa trước thay vì chỉ khi dẫn đầu.

---

### Productive Plan (積極策)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100402.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10008.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10042.png" alt="support hint" width="50" height="50"><br>


Slightly widen the margin when in the lead early-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==0&accumulatetime>=5& ~~order==1~~  **order_rate<=50** 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 1st to top 50%. Weaker version of Mile Maven with same condition change.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ nhất sang top 50%. Phiên bản yếu hơn của Mile Maven với cùng thay đổi điều kiện.

---

### Keen Eye (慧眼)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1040_104001.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30014.png" alt="support event" width="50" height="50"><br>


Decrease fatigue when positioned toward the back early-race. (Mile)

 **Changes:** 

Condition: distance_type==2& ~~phase_random~~  **phase_laterhalf_random** ==0& ~~accumulatetime>=5&~~ order_rate>50
Duration: ~~0~~ -> **3** 
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )
 **current_speed** : **-0.2** 
(Target: **ahead** , max **18** )

 **What Changed:** 

 **EN:** Three changes: (1) Changed to second half of early-race. (2) Duration increased from 0 to 3 seconds. (3) Added speed debuff (-0.2) on horses ahead. For Mile, now slows down front runners while recovering stamina.

 **VI:** Ba thay đổi: (1) Thay đổi sang nửa sau của đầu cuộc đua. (2) Thời lượng tăng từ 0 lên 3 giây. (3) Thêm debuff tốc độ (-0.2) cho ngựa phía trước. Với Mile, giờ làm chậm ngựa dẫn đầu trong khi hồi stamina.

---

### Watchful Eye (展開窺い)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1040_104001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20029.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10017.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10061.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30021.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10021.png" alt="support event" width="50" height="50"><br>


Slightly decrease fatigue when positioned toward the back early-race. (Mile)

 **Changes:** 

Condition: distance_type==2& ~~phase_random~~  **phase_laterhalf_random** ==0& ~~accumulatetime>=5&~~ order_rate>50
Duration: ~~0~~ -> **3** 
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )
 **current_speed** : **-0.05** 
(Target: **ahead** , max **18** )

 **What Changed:** 

 **EN:** Same changes as Keen Eye but weaker. Duration increased and added speed debuff (-0.05) on horses ahead. Weaker version with smaller effects.

 **VI:** Cùng thay đổi như Keen Eye nhưng yếu hơn. Thời lượng tăng và thêm debuff tốc độ (-0.05) cho ngựa phía trước. Phiên bản yếu hơn với hiệu ứng nhỏ hơn.

---

### Trackblazer (切り開く者)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1026_102601.png" alt="char" width="50" height="50"><br>


Decrease fatigue when in the lead mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order ~~==1~~  **<=3** 
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from only 1st place to top 3. For Medium distance, now activates when in top 3 positions instead of only when leading mid-race.

 **VI:** Yêu cầu vị trí nới lỏng từ chỉ vị trí thứ nhất sang top 3. Với cự ly Medium, giờ kích hoạt khi ở top 3 vị trí thay vì chỉ khi dẫn đầu giữa cuộc đua.

---

### Rosy Outlook (前途洋々)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1002_100201.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1026_102601.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10027.png" alt="support hint" width="50" height="50"><br>


Slightly decrease fatigue when in the lead mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order ~~==1~~  **<=3** 
Duration: 0
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement relaxed from 1st to top 3. Weaker version of Trackblazer with same condition change.

 **VI:** Yêu cầu vị trí nới lỏng từ thứ nhất sang top 3. Phiên bản yếu hơn của Trackblazer với cùng thay đổi điều kiện.

---

### Killer Tunes (キラーチューン)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1027_102701.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30007.png" alt="support event" width="50" height="50"><br>


Increase positioning ability when positioned toward the front mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order_rate<=50
Duration: ~~0.9~~ -> **2.4** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration massively increased from 0.9 to 2.4 seconds (167% increase). For Medium distance, speed boost lasts much longer when in top 50% mid-race.

 **VI:** Thời lượng tăng khủng từ 0.9 lên 2.4 giây (tăng 167%). Với cự ly Medium, tăng tốc độ kéo dài lâu hơn nhiều khi ở top 50% giữa cuộc đua.

---

### Up-Tempo (テンポアップ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1015_101501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1009_100901.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1014_101401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101801.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1027_102701.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30007.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30032.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30041.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30048.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20010.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20018.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10025.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10033.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10036.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10046.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10058.png" alt="support hint" width="50" height="50"><br>


Slightly increase positioning ability when positioned toward the front mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order_rate<=50
Duration: ~~0.9~~ -> **2.4** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 0.9 to 2.4 seconds (167% increase). Weaker version of Killer Tunes with same duration buff.

 **VI:** Thời lượng tăng từ 0.9 lên 2.4 giây (tăng 167%). Phiên bản yếu hơn của Killer Tunes với cùng buff thời lượng.

---

### Unyielding (勝利への執念)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30013.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30048.png" alt="support event" width="50" height="50"><br>


Increase ability to fight back when passed by another runner on the final corner. (Medium)

 **Changes:** 

Condition: distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime>0
Duration: 3
Cooldown:
500
speed: 0.35
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.1). For Medium distance, now gives both speed AND acceleration when getting passed on final corner.

 **VI:** Thêm tăng gia tốc (0.1). Với cự ly Medium, giờ tăng cả tốc độ VÀ gia tốc khi bị vượt ở khúc cua cuối.

---

### Steadfast (食い下がり)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100101.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30001.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30025.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30030.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30031.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30038.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30041.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20018.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10001.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10034.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10035.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10046.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10057.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10062.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30039.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10063.png" alt="support event" width="50" height="50"><br>


Slightly increase ability to fight back when passed by another runner on the final corner. (Medium)

 **Changes:** 

Condition: distance_type==3&is_finalcorner==1&corner!=0&change_order_onetime>0
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )
 **acceleration** : **0.05** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Added acceleration boost (0.05). Weaker version of Unyielding with lower values for both speed and acceleration.

 **VI:** Thêm tăng gia tốc (0.05). Phiên bản yếu hơn của Unyielding với giá trị thấp hơn cho cả tốc độ và gia tốc.

---

### Adrenaline Rush (火事場のバ鹿力)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20022.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30023.png" alt="support event" width="50" height="50"><br>


Regain the energy to run after exhausting strength. (Long)

 **Changes:** 

Condition: distance_type==4& ~~is_hp_empty_onetime==1~~  **hp_per<=30** 
Duration: 0
Cooldown:
500
hp_recovery: 0.055
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from one-time trigger when stamina hits zero to continuous trigger when stamina is 30% or below. For Long distance, now can activate multiple times instead of just once. Much more useful.

 **VI:** Thay đổi từ kích hoạt một lần khi stamina chạm 0 sang kích hoạt liên tục khi stamina ở 30% trở xuống. Với cự ly Long, giờ có thể kích hoạt nhiều lần thay vì chỉ một lần. Hữu ích hơn nhiều.

---

### Extra Tank (別腹タンク)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20021.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30022.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10055.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30001.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30023.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30025.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20019.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10001.png" alt="support event" width="50" height="50"><br>


Slightly regain the energy to run after exhausting strength. (Long)

 **Changes:** 

Condition: distance_type==4& ~~is_hp_empty_onetime==1~~  **hp_per<=30** 
Duration: 0
Cooldown:
500
hp_recovery: 0.015
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from one-time trigger to continuous trigger at 30% stamina or below. Weaker version of Adrenaline Rush with same condition change.

 **VI:** Thay đổi từ kích hoạt một lần sang kích hoạt liên tục ở 30% stamina trở xuống. Phiên bản yếu hơn của Adrenaline Rush với cùng thay đổi điều kiện.

---

### Sprint Corners ◎ (短距離コーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Sprint)

 **Changes:** 

Condition: distance_type==1& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation - now picks 4 random corner points with single condition instead of 4 separate conditions. For Sprint distance, easier to implement.

 **VI:** Kích hoạt đơn giản hơn - giờ chọn 4 điểm khúc cua ngẫu nhiên với một điều kiện thay vì 4 điều kiện riêng. Với cự ly Sprint, dễ triển khai hơn.

---

### Sprint Corners ○ (短距離コーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30015.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30040.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10018.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10064.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity on a corner. (Sprint)

 **Changes:** 

Condition: distance_type==1& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==1&corner_random==2@distance_type==1&corner_random==3@distance_type==1&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Sprint Corners ◎ with same condition change.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Sprint Corners ◎ với cùng thay đổi điều kiện.

---

### Staggering Lead (圧倒的リード)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1041_104101.png" alt="char" width="50" height="50"><br>


Increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase==1&bashin_diff_behind>= ~~5~~  **3** &order==1
Duration: ~~1.2~~ -> **3** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Two buffs: (1) Lead requirement reduced from 5 to 3 horse lengths - easier to activate. (2) Duration increased from 1.2 to 3 seconds (150% increase). For Sprint, activates earlier and lasts longer when leading.

 **VI:** Hai buff: (1) Yêu cầu dẫn trước giảm từ 5 xuống 3 thân ngựa - dễ kích hoạt hơn. (2) Thời lượng tăng từ 1.2 lên 3 giây (tăng 150%). Với Sprint, kích hoạt sớm hơn và kéo dài lâu hơn khi dẫn đầu.

---

### Huge Lead (大きなリード)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1041_104101.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30015.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10018.png" alt="support hint" width="50" height="50"><br>


Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase==1&bashin_diff_behind>= ~~5~~  **3** &order==1
Duration: ~~1.2~~ -> **3** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Lead requirement reduced and duration increased. Weaker version of Staggering Lead with same changes.

 **VI:** Yêu cầu dẫn trước giảm và thời lượng tăng. Phiên bản yếu hơn của Staggering Lead với cùng thay đổi.

---

### Plan X (プランX)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support event" width="50" height="50"><br>


Increase passing ability when positioned toward the front mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1& ~~phase_random~~  **phase_laterhalf_random** ==1&order>=2&order_rate<=50
Duration: 3
Cooldown:
500
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from random point to second half of mid-race. For Sprint, now activates in latter part of mid-race when 2nd+ in top 50%. More predictable timing.

 **VI:** Thay đổi từ điểm ngẫu nhiên sang nửa sau của giữa cuộc đua. Với Sprint, giờ kích hoạt ở phần sau của giữa cuộc đua khi thứ 2+ trong top 50%. Thời điểm dự đoán được hơn.

---

### Countermeasure (善後策)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1041_104101.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30015.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30040.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10018.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10064.png" alt="support hint" width="50" height="50"><br>


Slightly increase passing ability when positioned toward the front mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1& ~~phase_random~~  **phase_laterhalf_random** ==1&order>=2&order_rate<=50
Duration: 3
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed timing to second half of mid-race. Weaker version of Plan X with same timing change.

 **VI:** Thay đổi thời điểm sang nửa sau của giữa cuộc đua. Phiên bản yếu hơn của Plan X với cùng thay đổi thời điểm.

---

### Perfect Prep! (準備万全！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20052.png" alt="icon" width="50" height="50">



Prepare to make for the finish line mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==1
Duration: ~~3~~ -> **4** 
Cooldown:
500
lane_speed: 0.035
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 3 to 4 seconds (33% increase). For Sprint, navigation and acceleration boost lasts longer mid-race.

 **VI:** Thời lượng tăng từ 3 lên 4 giây (tăng 33%). Với Sprint, buff điều hướng và gia tốc kéo dài lâu hơn giữa cuộc đua.

---

### Meticulous Measures (仕掛け準備)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20051.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1038_103801.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30040.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10064.png" alt="support hint" width="50" height="50"><br>


Moderately prepare to make for the finish line mid-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==1
Duration: ~~3~~ -> **4** 
Cooldown:
500
lane_speed: 0.025
(Target: self, max 1 )
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 3 to 4 seconds. Weaker version of Perfect Prep! with same duration buff.

 **VI:** Thời lượng tăng từ 3 lên 4 giây. Phiên bản yếu hơn của Perfect Prep! với cùng buff thời lượng.

---

### Adored by All (悩殺術)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1038_103801.png" alt="char" width="50" height="50"><br>


Intimidate runners behind when positioned toward the front early-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==0& ~~order~~  **order_rate** <= ~~3~~  **50** &accumulatetime>=5
Duration: 3
Cooldown:
500
current_speed: -0.25
(Target: behind, max 18 )

 **What Changed:** 

 **EN:** Position requirement changed from top 3 places to top 50% of pack. For Sprint, easier to activate - now slows down horses behind you when in front half instead of only top 3.

 **VI:** Yêu cầu vị trí thay đổi từ top 3 vị trí sang top 50% đàn. Với Sprint, dễ kích hoạt hơn - giờ làm chậm ngựa phía sau khi ở nửa trước thay vì chỉ top 3.

---

### Intimidate (後方釘付)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1038_103801.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30015.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10018.png" alt="support hint" width="50" height="50"><br>


Moderately intimidate runners behind when positioned toward the front early-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==0& ~~order~~  **order_rate** <= ~~3~~  **50** &accumulatetime>=5
Duration: 3
Cooldown:
500
current_speed: -0.2
(Target: behind, max 18 )

 **What Changed:** 

 **EN:** Position requirement changed from top 3 to top 50%. Weaker version of Adored by All with same condition change.

 **VI:** Yêu cầu vị trí thay đổi từ top 3 sang top 50%. Phiên bản yếu hơn của Adored by All với cùng thay đổi điều kiện.

---

### You've Got No Shot (逃亡禁止令)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30052.png" alt="icon" width="50" height="50">



Cause panic in runners ahead when positioned toward the back early-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==0&order_rate>50&accumulatetime>=5
Duration: ~~0~~ -> **1.2** 
Cooldown:
500
hp_recovery: -0.03
(Target: ahead, max 18 )
 **acceleration** : **-0.2** 
(Target: **ahead** , max **18** )

 **What Changed:** 

 **EN:** Two changes: (1) Duration increased from instant (0) to 1.2 seconds. (2) Added acceleration debuff (-0.2) on horses ahead. For Sprint from back half, now drains stamina AND reduces acceleration of front runners for longer.

 **VI:** Hai thay đổi: (1) Thời lượng tăng từ tức thì (0) lên 1.2 giây. (2) Thêm debuff gia tốc (-0.2) cho ngựa phía trước. Với Sprint từ nửa sau, giờ hút stamina VÀ giảm gia tốc của ngựa dẫn đầu lâu hơn.

---

### Stop Right There! (抜け駆け禁止)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30051.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30020.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10042.png" alt="support hint" width="50" height="50"><br>


Slightly cause panic in runners ahead when positioned toward the back early-race. (Sprint)

 **Changes:** 

Condition: distance_type==1&phase_random==0&order_rate>50&accumulatetime>=5
Duration: ~~0~~ -> **1.2** 
Cooldown:
500
hp_recovery: -0.01
(Target: ahead, max 18 )
 **acceleration** : **-0.1** 
(Target: **ahead** , max **18** )

 **What Changed:** 

 **EN:** Duration increased and added acceleration debuff (-0.1). Weaker version of You've Got No Shot with same changes but lower values.

 **VI:** Thời lượng tăng và thêm debuff gia tốc (-0.1). Phiên bản yếu hơn của You've Got No Shot với cùng thay đổi nhưng giá trị thấp hơn.

---

### Mile Corners ◎ (マイルコーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Mile)

 **Changes:** 

Condition: distance_type==2& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation - single condition instead of 4 separate ones. For Mile distance, easier to implement.

 **VI:** Kích hoạt đơn giản hơn - một điều kiện thay vì 4 riêng biệt. Với cự ly Mile, dễ triển khai hơn.

---

### Mile Corners ○ (マイルコーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1005_100501.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20001.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10049.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10052.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity on a corner. (Mile)

 **Changes:** 

Condition: distance_type==2& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==2&corner_random==2@distance_type==2&corner_random==3@distance_type==2&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Mile Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Mile Corners ◎.

---

### Changing Gears (ギアチェンジ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"><br>


Increase passing ability when positioned toward the front mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==1&order_rate<=50
Duration: ~~1.2~~ -> **2.4** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration doubled from 1.2 to 2.4 seconds (100% increase). For Mile, speed boost lasts much longer when in top 50% mid-race.

 **VI:** Thời lượng tăng gấp đôi từ 1.2 lên 2.4 giây (tăng 100%). Với Mile, tăng tốc độ kéo dài lâu hơn nhiều khi ở top 50% giữa cuộc đua.

---

### Shifting Gears (ギアシフト)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1005_100501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1010_101001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30038.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30047.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10008.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10052.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10062.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20029.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20031.png" alt="support event" width="50" height="50"><br>


Slightly increase passing ability when positioned toward the front mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==1&order_rate<=50
Duration: ~~1.2~~ -> **2.4** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration doubled from 1.2 to 2.4 seconds. Weaker version of Changing Gears.

 **VI:** Thời lượng tăng gấp đôi từ 1.2 lên 2.4 giây. Phiên bản yếu hơn của Changing Gears.

---

### Step on the Gas! (アクセル全開！)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"><br>


Increase acceleration when passing another runner mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase==1&change_order_onetime<0
Duration: ~~1.2~~ -> **3** 
Cooldown:
500
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.2 to 3 seconds (150% increase). For Mile, acceleration boost lasts much longer when overtaking mid-race.

 **VI:** Thời lượng tăng từ 1.2 lên 3 giây (tăng 150%). Với Mile, tăng gia tốc kéo dài lâu hơn nhiều khi vượt giữa cuộc đua.

---

### Acceleration (アクセラレーション)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100401.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1006_100601.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1040_104001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30042.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10004.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10017.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10065.png" alt="support hint" width="50" height="50"><br>


Slightly increase acceleration when passing another runner mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase==1&change_order_onetime<0
Duration: ~~1.2~~ -> **3** 
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.2 to 3 seconds. Weaker version of Step on the Gas!

 **VI:** Thời lượng tăng từ 1.2 lên 3 giây. Phiên bản yếu hơn của Step on the Gas!

---

### Big-Sisterly (姉御肌)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1005_100501.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101802.png" alt="char" width="50" height="50"><br>


Increase passing ability. (Mile)

 **Changes:** 

Condition: distance_type==2&is_overtake==1&accumulatetime>=5
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds (33% increase). For Mile, speed boost lasts longer when overtaking after 5 seconds.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây (tăng 33%). Với Mile, tăng tốc độ kéo dài lâu hơn khi vượt sau 5 giây.

---

### Unyielding Spirit (負けん気)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30013.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30048.png" alt="support event" width="50" height="50"><br>


Slightly increase passing ability. (Mile)

 **Changes:** 

Condition: distance_type==2&is_overtake==1&accumulatetime>=5
Duration: ~~1.8~~ -> **2.4** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 2.4 seconds. Weaker version of Big-Sisterly.

 **VI:** Thời lượng tăng từ 1.8 lên 2.4 giây. Phiên bản yếu hơn của Big-Sisterly.

---

### Greed for Speed (スピードグリード)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30012.png" alt="icon" width="50" height="50">



Moderately steal velocity from runners behind when in the lead mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==1&order ~~==1~~  **<=3** 
Duration: 3
Cooldown:
500
current_speed: -0.2
(Target: behind, max 5 )
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position relaxed from 1st only to top 3. Slows horses behind while boosting your speed when in top 3 mid-race for Mile.

 **VI:** Vị trí nới lỏng từ chỉ thứ nhất sang top 3. Làm chậm ngựa phía sau trong khi tăng tốc độ của bạn khi ở top 3 giữa cuộc đua với Mile.

---

### Speed Eater (スピードイーター)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1004_100402.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10035.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10052.png" alt="support hint" width="50" height="50"><br>


Slightly steal velocity from runners behind when in the lead mid-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==1&order ~~==1~~  **<=3** 
Duration: 3
Cooldown:
500
current_speed: -0.15
(Target: behind, max 5 )
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position relaxed from 1st to top 3. Weaker version of Greed for Speed.

 **VI:** Vị trí nới lỏng từ thứ nhất sang top 3. Phiên bản yếu hơn của Greed for Speed.

---

### Battle Formation (布陣)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30022.png" alt="icon" width="50" height="50">



Dull movement for runners ahead when positioned toward the back early-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==0&order_rate>50&accumulatetime>= ~~5~~  **3** 
Duration: 3
Cooldown:
500
acceleration: -0.3
(Target: ahead, max 18 )

 **What Changed:** 

 **EN:** Wait time reduced from 5 to 3 seconds. Activates earlier, reducing acceleration of front runners for Mile from back half.

 **VI:** Thời gian chờ giảm từ 5 xuống 3 giây. Kích hoạt sớm hơn, giảm gia tốc của ngựa dẫn đầu với Mile từ nửa sau.

---

### Opening Gambit (布石)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30021.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20005.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10026.png" alt="support hint" width="50" height="50"><br>


Slightly dull movement for runners ahead when positioned toward the back early-race. (Mile)

 **Changes:** 

Condition: distance_type==2&phase_random==0&order_rate>50&accumulatetime>= ~~5~~  **3** 
Duration: 3
Cooldown:
500
acceleration: -0.1
(Target: ahead, max 18 )

 **What Changed:** 

 **EN:** Wait time reduced from 5 to 3 seconds. Weaker version of Battle Formation.

 **VI:** Thời gian chờ giảm từ 5 xuống 3 giây. Phiên bản yếu hơn của Battle Formation.

---

### Medium Corners ◎ (中距離コーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Medium)

 **Changes:** 

Condition: distance_type==3& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for Medium distance.

 **VI:** Kích hoạt đơn giản hơn với cự ly Medium.

---

### Medium Corners ○ (中距離コーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1037_103701.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1058_105801.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1032_103201.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30029.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30031.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30038.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30044.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20011.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20035.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10027.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10034.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10036.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10056.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10062.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10070.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10072.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30032.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10058.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity on a corner. (Medium)

 **Changes:** 

Condition: distance_type==3& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==3&corner_random==2@distance_type==3&corner_random==3@distance_type==3&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Medium Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Medium Corners ◎.

---

### Lightning Step (ライトニングステップ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20052.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100301.png" alt="char" width="50" height="50"><br>


Avoid becoming surrounded when positioned toward the back mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order_rate>50
Duration: ~~3~~ -> **4** 
Cooldown:
500
lane_speed: 0.035
(Target: self, max 1 )
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 3 to 4 seconds. Navigation and acceleration buff lasts longer for Medium from back half.

 **VI:** Thời lượng tăng từ 3 lên 4 giây. Buff điều hướng và gia tốc kéo dài lâu hơn với Medium từ nửa sau.

---

### Thunderbolt Step (イナズマステップ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20051.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1001_100102.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100301.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10027.png" alt="support hint" width="50" height="50"><br>


Moderately avoid becoming surrounded when positioned toward the back mid-race. (Medium)

 **Changes:** 

Condition: distance_type==3&phase_random==1&order_rate>50
Duration: ~~3~~ -> **4** 
Cooldown:
500
lane_speed: 0.025
(Target: self, max 1 )
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 3 to 4 seconds. Weaker version of Lightning Step.

 **VI:** Thời lượng tăng từ 3 lên 4 giây. Phiên bản yếu hơn của Lightning Step.

---

### Long Corners ◎ (長距離コーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Long)

 **Changes:** 

Condition: distance_type==4& ~~corner_random~~  **all_corner_random** ==1 ~~@distance_type==4&corner_random==2@distance_type==4&corner_random==3@distance_type==4&corner_random==4~~ 
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for Long distance.

 **VI:** Kích hoạt đơn giản hơn với cự ly Long.

---

### Long Corners ○ (長距離コーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101301.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10010.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10055.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity on a corner. (Long)

 **Changes:** 

Condition: distance_type==4& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Long Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Long Corners ◎.

---

### Vanguard Spirit (先陣の心得)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20012.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1020_102001.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30027.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30055.png" alt="support event" width="50" height="50"><br>


Increase ability to maintain the lead when leading by a large margin mid-race. (Long)

 **Changes:** 

Condition: distance_type==4&phase_random==1&bashin_diff_behind>= ~~3~~  **1** &order==1
Duration: 3
Cooldown:
500
speed: 0.35
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Lead requirement reduced from 3 to 1 horse length. Much easier to activate for Long distance when leading mid-race.

 **VI:** Yêu cầu dẫn trước giảm từ 3 xuống 1 thân ngựa. Dễ kích hoạt hơn nhiều với cự ly Long khi dẫn đầu giữa cuộc đua.

---

### Keeping the Lead (リードキープ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1013_101301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1020_102001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_10010.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30008.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30027.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30055.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10014.png" alt="support event" width="50" height="50"><br>


Slightly increase ability to maintain the lead when leading by a large margin mid-race. (Long)

 **Changes:** 

Condition: distance_type==4&phase_random==1&bashin_diff_behind>= ~~3~~  **1** &order==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Lead requirement reduced from 3 to 1 horse length. Weaker version of Vanguard Spirit.

 **VI:** Yêu cầu dẫn trước giảm từ 3 xuống 1 thân ngựa. Phiên bản yếu hơn của Vanguard Spirit.

---

### Front Runner Corners ◎ (逃げコーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Front Runner)

 **Changes:** 

Condition: running_style==1& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for Front Runner style.

 **VI:** Kích hoạt đơn giản hơn cho phong cách Front Runner.

---

### Front Runner Corners ○ (逃げコーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1026_102601.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20009.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10032.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity on a corner. (Front Runner)

 **Changes:** 

Condition: running_style==1& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Front Runner Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Front Runner Corners ◎.

---

### Sixth Sense (シックスセンス)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20052.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30040.png" alt="support event" width="50" height="50"><br>


Avoid becoming surrounded early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase==0& ~~blocked_all_continuetime~~  **blocked_front_continuetime** >=1 **@running_style==1&phase==0&blocked_side_continuetime>=1** 
Duration: 3
Cooldown:
500
lane_speed: 0.035
(Target: self, max 1 )
 **new_unkn_35** : **0.5** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Changed to trigger when blocked from front OR side (instead of all directions). Added unknown stat (0.5). More flexible activation for Front Runners early-race.

 **VI:** Thay đổi sang kích hoạt khi bị chặn từ trước HOẶC bên (thay vì tất cả hướng). Thêm chỉ số chưa rõ (0.5). Kích hoạt linh hoạt hơn cho Front Runner đầu cuộc đua.

---

### Dodging Danger (危険回避)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20051.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10055.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30040.png" alt="support event" width="50" height="50"><br>


Moderately avoid becoming surrounded early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase==0& ~~blocked_all_continuetime~~  **blocked_front_continuetime** >=1 **@running_style==1&phase==0&blocked_side_continuetime>=1** 
Duration: 3
Cooldown:
500
lane_speed: 0.025
(Target: self, max 1 )
 **new_unkn_35** : **0.5** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Changed blocking detection and added unknown stat. Weaker version of Sixth Sense.

 **VI:** Thay đổi phát hiện bị chặn và thêm chỉ số chưa rõ. Phiên bản yếu hơn của Sixth Sense.

---

### Leader's Pride (先頭プライド)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102401.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10002.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10051.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30026.png" alt="support event" width="50" height="50"><br>


Slightly avoid being passed early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase ~~==0~~  **<=1** &change_order_onetime>0&accumulatetime>=5 **@running_style==1&phase<=1&blocked_side_continuetime>=2&accumulatetime>=5** 
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Phase expanded from early-race only to early+mid-race. Added alternative condition for side blocking. More activation opportunities for Front Runners when getting passed or blocked.

 **VI:** Giai đoạn mở rộng từ chỉ đầu cuộc đua sang đầu+giữa cuộc đua. Thêm điều kiện thay thế cho bị chặn bên. Nhiều cơ hội kích hoạt hơn cho Front Runner khi bị vượt hoặc chặn.

---

### Reignition (再燃焼)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">



Increase acceleration when positioned toward the back mid-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase_random==1& ~~order_rate>50~~  **order>=2** 
Duration: 3
Cooldown:
500
acceleration: 0.4
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from percentage-based (back 50%) to position-based (2nd or worse). For Front Runners who lost lead, triggers when 2nd or lower mid-race.

 **VI:** Thay đổi từ dựa phần trăm (50% sau) sang dựa vị trí (thứ 2 trở xuống). Cho Front Runner mất dẫn đầu, kích hoạt khi thứ 2 hoặc thấp hơn giữa cuộc đua.

---

### Second Wind (二の矢)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30017.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10039.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30008.png" alt="support event" width="50" height="50"><br>


Slightly increase acceleration when positioned toward the back mid-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase_random==1& ~~order_rate>50~~  **order>=2** 
Duration: 3
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed from percentage to position-based. Weaker version of Reignition.

 **VI:** Thay đổi từ phần trăm sang dựa vị trí. Phiên bản yếu hơn của Reignition.

---

### Restart (リスタート)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_30021.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30017.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10039.png" alt="support hint" width="50" height="50"><br>


Slightly startle runners ahead when failing to get a lead early-race. (Front Runner)

 **Changes:** 

Condition: running_style==1&phase_random==0& ~~order_rate>50~~  **order>=2** &accumulatetime>=5
Duration: 3
Cooldown:
500
acceleration: -0.1
(Target: ahead, max 18 )

 **What Changed:** 

 **EN:** Changed from percentage to position-based (2nd or worse). Reduces acceleration of horses ahead when Front Runner fails to take lead early.

 **VI:** Thay đổi từ phần trăm sang dựa vị trí (thứ 2 trở xuống). Giảm gia tốc của ngựa phía trước khi Front Runner không dẫn đầu sớm.

---

### Pace Chaser Corners ◎ (先行コーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for Pace Chaser style.

 **VI:** Kích hoạt đơn giản hơn cho phong cách Pace Chaser.

---

### Pace Chaser Corners ○ (先行コーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1017_101701.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1018_101802.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30018.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20027.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20034.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10041.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10069.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20017.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10045.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity on a corner. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Pace Chaser Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Pace Chaser Corners ◎.

---

### Technician (技巧派)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100301.png" alt="char" width="50" height="50"><br>


Moderately increase ability to navigate smoothly. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&is_move_lane==1@running_style==2&is_move_lane==2
Duration: ~~1.8~~ -> **3** 
Cooldown:
500
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds (67% increase). Acceleration boost lasts longer when Pace Chasers change lanes.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây (tăng 67%). Tăng gia tốc kéo dài lâu hơn khi Pace Chaser đổi làn.

---

### Shrewd Step (巧みなステップ)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1003_100301.png" alt="char" width="50" height="50"> <img src="https://gametora.com/images/umamusume/characters/chara_stand_1024_102402.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20028.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10003.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10059.png" alt="support hint" width="50" height="50"><br>


Slightly increase ability to navigate smoothly. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&is_move_lane==1@running_style==2&is_move_lane==2
Duration: ~~1.8~~ -> **3** 
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds. Weaker version of Technician.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây. Phiên bản yếu hơn của Technician.

---

### Determined Descent (決意の直滑降)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1030_103001.png" alt="char" width="50" height="50"><br>


Moderately improve running on a downhill. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~slope~~  **down_slope_random** == ~~2~~  **1** 
Duration: 3
Cooldown:
500
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed to more specific downhill detection and changed value. Now triggers at downhill points for Pace Chasers.

 **VI:** Thay đổi sang phát hiện dốc xuống cụ thể hơn và thay đổi giá trị. Giờ kích hoạt tại điểm dốc xuống cho Pace Chaser.

---

### Straight Descent (直滑降)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1030_103001.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30023.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10015.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20024.png" alt="support event" width="50" height="50"><br>


Slightly improve running on a downhill. (Pace Chaser)

 **Changes:** 

Condition: running_style==2& ~~slope~~  **down_slope_random** == ~~2~~  **1** 
Duration: 3
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Changed detection. Weaker version of Determined Descent.

 **VI:** Thay đổi phát hiện. Phiên bản yếu hơn của Determined Descent.

---

### Shatterproof (くじけぬ精神)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30044.png" alt="support event" width="50" height="50"><br>


Moderately increase acceleration when positioned toward the back mid-race. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&phase_random==1&order_rate> ~~50~~  **40** 
Duration: 3
Cooldown:
500
acceleration: 0.3
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position requirement changed from back 50% to back 60%. Easier to activate for Pace Chasers further back mid-race.

 **VI:** Yêu cầu vị trí thay đổi từ 50% sau sang 60% sau. Dễ kích hoạt hơn cho Pace Chaser ở xa hơn phía sau giữa cuộc đua.

---

### Tactical Tweak (まき直し)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20041.png" alt="icon" width="50" height="50">

**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30039.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10012.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10063.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20002.png" alt="support event" width="50" height="50"><br>


Slightly increase acceleration when positioned toward the back mid-race. (Pace Chaser)

 **Changes:** 

Condition: running_style==2&phase_random==1&order_rate> ~~50~~  **40** 
Duration: 3
Cooldown:
500
acceleration: 0.2
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Position changed to back 60%. Weaker version of Shatterproof.

 **VI:** Vị trí thay đổi sang 60% sau. Phiên bản yếu hơn của Shatterproof.

---

### Later Surger Corners ◎ (差しコーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (Late Surger)

 **Changes:** 

Condition: running_style==3& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for Late Surger style.

 **VI:** Kích hoạt đơn giản hơn cho phong cách Late Surger.

---

### Late Surger Corners ○ (差しコーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20013.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_20016.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10038.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10044.png" alt="support hint" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30012.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30033.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_30046.png" alt="support event" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10016.png" alt="support event" width="50" height="50"><br>


Slightly increase velocity on a corner. (Late Surger)

 **Changes:** 

Condition: running_style==3& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of Later Surger Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của Later Surger Corners ◎.

---

### Hard Worker (努力家)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20042.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1035_103501.png" alt="char" width="50" height="50"><br>
**Support (Event):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_30046.png" alt="support event" width="50" height="50"><br>


Moderately improve running late-race. (Late Surger)

 **Changes:** 

Condition: running_style==3&phase_random==2
Duration: ~~1.8~~ -> **3** 
Cooldown:
500
speed: 0.25
(Target: self, max 1 )
 **acceleration** : **0.1** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds. Added acceleration boost (0.1). For Late Surgers, now gets both speed AND acceleration in late-race phase.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây. Thêm tăng gia tốc (0.1). Cho Late Surger, giờ được cả tốc độ VÀ gia tốc trong giai đoạn cuối cuộc đua.

---

### Diligence (直向き)
Slightly improve running late-race. (Late Surger)

 **Changes:** 

Condition: running_style==3&phase_random==2
Duration: ~~1.8~~ -> **3** 
Cooldown:
500
speed: 0.15
(Target: self, max 1 )
 **acceleration** : **0.05** 
(Target: **self** , max **1** )

 **What Changed:** 

 **EN:** Duration increased from 1.8 to 3 seconds. Added acceleration boost (0.05). Weaker version of Hard Worker with same changes.

 **VI:** Thời lượng tăng từ 1.8 lên 3 giây. Thêm tăng gia tốc (0.05). Phiên bản yếu hơn của Hard Worker với cùng thay đổi.

---

### End Closer Corners ◎ (追込コーナー◎)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">



Moderately increase velocity on a corner. (End Closer)

 **Changes:** 

Condition: running_style==4& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.25
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation for End Closer style.

 **VI:** Kích hoạt đơn giản hơn cho phong cách End Closer.

---

### End Closer Corners ○ (追込コーナー○)

<img src="https://gametora.com/images/umamusume/skill_icons/utx_ico_skill_20011.png" alt="icon" width="50" height="50">

**Character:** <br>
 <img src="https://gametora.com/images/umamusume/characters/chara_stand_1012_101201.png" alt="char" width="50" height="50"><br>
**Support (Hint):** <br>
 <img src="https://gametora.com/images/umamusume/supports/support_card_s_20014.png" alt="support hint" width="50" height="50"> <img src="https://gametora.com/images/umamusume/supports/support_card_s_10040.png" alt="support hint" width="50" height="50"><br>


Slightly increase velocity on a corner. (End Closer)

 **Changes:** 

Condition: running_style==4& ~~corner_random~~  **all_corner_random** ==1
Duration: 3
Cooldown:
500
speed: 0.15
(Target: self, max 1 )

 **What Changed:** 

 **EN:** Simplified activation. Weaker version of End Closer Corners ◎.

 **VI:** Kích hoạt đơn giản hơn. Phiên bản yếu hơn của End Closer Corners ◎.

---
