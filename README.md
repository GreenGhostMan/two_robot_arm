ROS MYANMAR TEAM
INTRO 
  
  <img src="https://github.com/GreenGhostMan/two_robot_arm/blob/master/two_arm.jpg"/>
  
  1) Master / Slave mode
အရင်ဆုံး controller_two_arms_manual.sh ကို run ပါ 
ပီးရင် controller_two_arms_manual.launch ကို run ပါ
ပထမ sh က actuator တွေကို zeroing လုပ်လိုက်ပီး slave လုပ်မဲ့ arm ကို torque တွေလျော့လိုက်ပါသည်
controller_two_arms_manual.launch ကတော့ controller.launch ကိုပဲပြန်ရေးထားတာဖြစ်ပီး republisher node ကို ထပ်ထဲ့ထားပါသည်
republisher node ကတော့ master arm ရဲ့ servo state ကို  slave arm ရဲ့ command အဖြစ် publish ပြန်လုပ်ပေးပါသည်
  



