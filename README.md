<h2> ROS MYANMAR TEAM <h2>
<h3> INTRO </h3>
  
  <img src="https://github.com/GreenGhostMan/two_robot_arm/blob/master/two_arm.jpg" width="350" height="300"/>
<h4>  1) Controller </h4>
Controller.launch သည် အခြေခံကျဆုံးသော launch ဖိုင်ဖြစ်ပီး အခြား launch များမှ နမူနာ သုံးစွဲကြရန်ဖြစ်ပါသည်။
controller.launch ရဲ့ controller spawner node တွင် ros_mm_arm တစ်ခုအတွက်သာ joint အရေအတွက်ထဲ့ထားပါသည်။
<h4>  2) Master / Slave mode </h4>
အရင်ဆုံး controller_two_arms_manual.sh ကို run ပါ။ <br>
ပီးရင် controller_two_arms_manual.launch ကို run ပါ။ <br>
ပထမ sh က actuator တွေကို zeroing လုပ်လိုက်ပီး slave လုပ်မဲ့ arm ကို torque တွေလျော့လိုက်ပါသည်။ <br>
controller_two_arms_manual.launch ကတော့ controller.launch ကိုပဲပြန်ရေးထားတာဖြစ်ပီး republisher node ကို ထပ်ထဲ့ထားပါသည်။ <br>
republisher node ကတော့ master arm ရဲ့ servo state ကို  slave arm ရဲ့ command အဖြစ် publish ပြန်လုပ်ပေးပါသည်။ <br>
controller.launch ကို ပြင်ရေးတဲ့အခါ ros_mm_arm ၂ ခုအတွက် controller spawner များတွင်ရေးထားပါသည်။
<h4> 3) Moveit </h4>
Moveit နဲ့ရေးရာမှာတော့ dual positon controller အနေနဲ့ရေးပါသည်။
yaml ဖိုင်များ ကိုလေ့လာကြည့်ပါ။
  



