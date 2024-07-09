Only Linux Operting System

![Screenshot from 2024-07-09 12-05-29](https://github.com/joyson04/eve-ng-connect-real-network/assets/113278417/fdbb5c1c-d857-4a94-87a1-9547ebd82825)

step : 2
  
  step : 1 
    select : Bridge apadator
  step : 2 
    select : Repliacte physical  network connection state
  step : 3
     save .
     
![Screenshot from 2024-07-09 12-06-06](https://github.com/joyson04/eve-ng-connect-real-network/assets/113278417/73342875-6171-47f3-8ace-8024db1305d7)

Ubuntu operting system enter command:

step: 1
ls -l /dev/vmnet0

ubuntu:~$ ls -l /dev/vmnet0
crwxrwxrwx 1 root root 119, 0 Jul  9 10:20 /dev/vmnet0

step:2 
sudo chmod 777  /dev/vmnet0

step:3 
restart eve-ng on vmware

![Screenshot from 2024-07-09 12-41-46](https://github.com/joyson04/eve-ng-connect-real-network/assets/113278417/2eec27e1-1fe5-4688-9cdc-2927c08b43a1)


![Screenshot from 2024-07-09 12-38-17](https://github.com/joyson04/eve-ng-connect-real-network/assets/113278417/37cf2625-8299-414f-8d6f-c37e1c468a86)

Router1:
  ping 8.8.8.8 (google dns)
![Screenshot from 2024-07-09 12-39-11](https://github.com/joyson04/eve-ng-connect-real-network/assets/113278417/7f33ef69-ea1b-41a6-a040-52a9c407a78e)
