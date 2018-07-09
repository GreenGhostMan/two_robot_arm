ROS MYANMAR TEAM
INTRO 
  
  <img src="https://github.com/GreenGhostMan/two_robot_arm/blob/master/two_arm.jpg"/>
  
<h2>  1) Master / Slave mode </h2>
အရင်ဆုံး controller_two_arms_manual.sh ကို run ပါ <br>
ပီးရင် controller_two_arms_manual.launch ကို run ပါ <br>
ပထမ sh က actuator တွေကို zeroing လုပ်လိုက်ပီး slave လုပ်မဲ့ arm ကို torque တွေလျော့လိုက်ပါသည် <br>
controller_two_arms_manual.launch ကတော့ controller.launch ကိုပဲပြန်ရေးထားတာဖြစ်ပီး republisher node ကို ထပ်ထဲ့ထားပါသည် <br>
republisher node ကတော့ master arm ရဲ့ servo state ကို  slave arm ရဲ့ command အဖြစ် publish ပြန်လုပ်ပေးပါသည် <br>
  



