

# Create an upcoming events component for homepage
___________     _________         _________
|         |     |upcoming   |    |Home    |
|events.md|-->  |events.astro|--> |Page    |
|_________|     |____________|    |_______ |

How the component will function :
The homepage has an upcoming event section. This section displays the next event

An event has the following schema :
1. type => evening stargazing, overnight,moonlight stargazing etc. (check out @cosmicvetures_) for such event pics
2. location => mollem, siolim etc
3. date =>

These fields will be edited by site adminds later in upcoming-event.md file in src/content folder
So that website can show the latest event without needing to change the code or design

Our task is to write the UpComingEvents.astro component that reads this markdown file and displays the event accordingly
This component is already created in src/sections folder and already imorted in homepage (index.astro). Just have to write the appropritate code in it
