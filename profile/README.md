![5eed1ab](https://5eed1ab.com/images/ibm029encoding.jpg)

|Release Engineering|Learning more then working|
|--|--|
|<img width="500" height="608" alt="1598051634015" src="https://github.com/user-attachments/assets/6a659d49-b9ee-4457-b7a8-facdd457a7e2" />|<img width="960" height="500" alt="1599233299799" src="https://github.com/user-attachments/assets/9b973b49-b4e2-466d-bd9b-9ab5fd66b2ec" />|

After some time to rest was able to realise **I never really knew how Computers work**
-  [How a Gutenberg Printing Press Works](https://www.youtube.com/watch?v=DLctAw4JZXE)
-  [Bye Bye Babbage: the most awesome mechanical calculator good bye party](https://www.youtube.com/watch?v=GB1xQkgi3HE)
-  [Automatic Punch Card Making For Jacquard Loom](https://www.youtube.com/watch?v=XmmDYcdmsxQ)
-  [The Fascinating Story of Bell Labs, the American Laboratory That Invented the Modern World](https://www.youtube.com/watch?v=mskbVYpj208)
-  [Claude Shannon - The Bit Player Movie Trailer](https://www.youtube.com/watch?v=E3OldEtfBrE)
-  [The Shannon Limit - Bell Labs - Future Impossible](https://www.youtube.com/watch?v=HSoog0OqgV0)
-  [A Theory, A Paper, A Turning Point: Claude Shannon's 1948 'Mathematical Theory of Communication](https://www.youtube.com/watch?v=uH401UXIX4o)
-  [The punched card tabulator](https://www.ibm.com/history/punched-card-tabulator)
-  [IBM: Once Upon A Punched Card 1964 Vintage computing](https://www.youtube.com/watch?v=BlUWg2nxCz0)
-  [card punch typography](https://www.masswerk.at/nowgobang/2020/card-punch-typography)
-  [A provocation to Think!](https://www.ibm.com/history/thomas-watson-sr)

![think](https://assets.ibm.com/is/image/ibm/5527_WatsonSr_Karsh?dpr=on%2C2&wid=1584&hei=2005)

| ThinkPad E16 |ThinkCentre M52 | ThinkStation S30 | ThinkStation P310 |
|--------------|----------------|------------------|-------------------|
| <img width="500" height="500" alt="s-l500" src="https://github.com/user-attachments/assets/c40a4b23-f09c-41c0-abad-2f2c99562ce9" /> | <img width="521.5" height="282" alt="s-l1600" src="https://github.com/user-attachments/assets/d617739f-de01-4003-add6-b9177695077e" /> | <img width="500" height="500" alt="s-l1600" src="https://github.com/user-attachments/assets/7d3bd2c2-e42d-489f-8971-a4e8ee2d7c0a" /> | <img width="500" height="485" alt="s-l500-1" src="https://github.com/user-attachments/assets/26678649-a66a-4ee9-aeec-2ee3d05e3eb8" /> |

### ThinkPad E16
- It already has Windows 11 and Internet access. Going to install RHEL WSL with git, gcc, gdb, make, and podman.
- Gutenberg is a FreeBSD Virtual Machine with zfs on 3 virtual disks, Gitea, Samba

### ThinkCentre M52
- Restricted System with no internet access
- Pentium 4, my oldest x64 system
- Can we migrate Gutenberg from the ThinkPad to physical HDDs?
- 2.5Gb PCIe Nic
if it can't keep up, upgrade to SSDs, can it now?
 
## ThinkStation S30
- Restricted System with no internet access
- Xeon with ECC Ram, room for 3.5 HHDs, PCIe slot for 10 Gb Nic, NVMe card.
Take it all apart and re-build it.
Can we move Gutenberg from the ThinkCentre?

### ThinkStation P310
- Restricted System with no internet access
- Smaller, faster Xeon with ECC Ram
- Can we move Gutenberg from the S30?

## continually finding ways to bridge creative ideas with engineering rigor

"Here’s to the [crazy ones](https://www.thecrazyones.it). The misfits. The rebels. The troublemakers. The round pegs in the square holes. The ones who see things differently. They’re not fond of rules. And they have no respect for the status quo. You can quote them, disagree with them, glorify or vilify them. About the only thing you can’t do is ignore them. Because they change things. They push the human race forward. And while some may see them as the crazy ones, we see genius. Because the people who are crazy enough to think they can change the world, are the ones who do."

- [Shaan Sahota Writer's Portrait | The Estate | National Theatre](https://youtu.be/hGFabrQb6Bg?si=3Z04YCn9X2rnEmnW&t=532)

|[Ansel](https://www.youtube.com/watch?v=IyT3YuY2V8c)|[Pablo](https://www.youtube.com/watch?v=Nxes8pyHkJc)|[Jimi](https://www.youtube.com/watch?v=bBTtPPnkkGk)|[Amelia](https://www.youtube.com/watch?v=adtxXNcvu8U)|
|--|--|--|--|
|![Ansel](https://www.thecrazyones.it/poster/anseladams.jpg)|![Pablo](https://www.thecrazyones.it/poster/pablopicasso.jpg)|![jimi](https://www.thecrazyones.it/poster/jimihendrix.jpg)|![Amelia](https://www.thecrazyones.it/poster/ameliaearhart.jpg)

-  [ASCII art demo with vintage HP 85 computer, HP 7970E 9-track tape and HP 2631G dot matrix printer](https://www.youtube.com/watch?v=YS9dGYUbNd0)
```
Practical Ca7                                                            1000001
▒▒░░░░░   ░▒▓█████▒░░░  ░░  ░░▓▒▒ ░▒▒░ ░░▓▓░░▓▒░░░░ ▒░ ░  ▒████████▓▒░ ░░░░░░░▒▒
▒▒▒░░░░░░▒███▓▓▒▒▒▓███▒░    ░▒▒░▒░░▓ ░░░▒▒▒▓▓▓▓▒░ ░░░░▒████▒▓░▓▓▓▓██▓░░░▓▒░░░░▒▒
░▒▒░░░░░ ░▓█▒░░▒▒ ░█░▒▓█▓░░   ░▓▒░▒░▒▒░░░░░▒▒█▓░░░░░▓███▒░█░▒▒░ ░░▓▓░   ░▒▓▒░▒▒░
▒░░░░░░░  ▒█░  ░░░███░▒▒▒▒░░  ░▒▒░▒▒▒░░░░░▒▒▓▓▒░ ░░█▓▓▒▒▒███░░░░  █▒      ░░▒▒▒▒
▓░▒▒░░░░ ░ ░▓░  ░░███░░░░░█░  ░░░▒░░░░░░░▒▒▒▓▓▒ ░░▒██▒░▒░███░░░░ ▓▒    ░ ░░▒▓▓▒▒
▒░░▒░░░     ░▒▓  ░ █░░░ ░██▓░░░▒▒░ ░   ░░░▒░▒▒▒░░░▓██▓░░▒░█ ░░ ▓░   ░░░░ ░░▒▓▓▒▒
▒░░▒▒▒░░░░      ▒▓▒▒▓▓▓▓▓▒▒▒░░▒░░░░░░░░░░▒▒▒▓▓▒▒▒▒▓▓▒▓▒▓▓▓▓▓░░     ░░░░░▒░▒▓▓▓▓▒
```
-  [Hexadecimal mechanical calculator from the 1970s](https://www.youtube.com/watch?v=BunhaYGDl88)
`5E:ED:1A:BC:A7:0A`
- [The Power to Change](https://www.youtube.com/watch?v=SyUmdrXvVVg)
- should we also teach?
  - ascii along with the alphabet
  - base 2 counting along with base 10
  - Git for everyone. It isn't just source control.
    - it's a time machine for thinking
    - it's the modern version of the gutenberg press

## Is it necessary to build a Computer, install an Operating Systems, and learn C these days?

[How Books Are Handmade At The Last Printing Press Of Its Kind In The US | Still Standing](https://www.youtube.com/watch?v=Q1xKcRrn_i4)

## Practical Ca7 is a hands-on journey 
Learning C, taking advantage of Git, Gitea while also learing ZFS so we can migrate to faster systems. What programs can be written to learn enough math to understand [A Mathematical Theory of Communication](https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf) 

https://www.masswerk.at/keypunch
![5eed1ab](https://5eed1ab.com/images/card.png)

[5EED1AB PRACTICAL CA7 1000001](https://github.com/5eed1ab/practical)
