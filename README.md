# Spatial Future

## NEW PROJECT: BikemappingZRH
![Bikemap Paris](https://raw.githubusercontent.com/posmocoop/spatial_future/master/paris.jpeg)
Vorbild: Bikemap Paris

The idea is to map the time you need between important locations in Zurich when on a bike.     
Thomas Hug has created a map of important locations and started measuring the duration between them. Roger Fischer has equally started to measure others and proposes a [simple csv structure](https://github.com/posmocoop/spatial_future/blob/master/bikemappingzrh.csv) to capture the times (and maybe even the distances).   

To be very precise, we use Posmo Segments available in the [App Store](https://apps.apple.com/us/app/posmo-segments/id1450602777) and [Google Play Store](https://play.google.com/store/apps/details?id=io.datamap.posmo_segments). As more people add their times, the distribution will become richer. And the better we can calculate a median duration value.             

### CSV
Record your segment from origin to destination. Try to be as near as possible to a location. If it is a public transport station, try to be on the nearest street available for bikes as if you would compete against a tram or bus and you have both the same starting and finishing line, each in its lane.              
             
- origin = start of a segment 
- destination = end of a segment
- distance in meters
- times in seconds (see below)
           
For every person joining, we will use initials (e.g. rf, th) and numbers for every recording. We will precede it by bike, ebike25 (E-Bike 25km/h) or sped45 (for S-Pedelec 45km/h) for normal bikes and ebikes. E.g. ebike25_th1 = Thomas Hug first recording when using an E-Bike.             
Question: Should we differentiate city bikes from racing bikes?         
            
Once you have your times, please make a pull request to update the file and propose a handle.          

### Visualization
Thomas Hug is already working on this. And everyone can use and visualize the data at their convenience. If you do so, you need to use the mention "Ein Projekt der Genossenschaft POSMO Schweiz" or "A project by the Cooperative POSMO Switzerland". 

### Why we don't want to automate this for now
Simplicity beats complexity. Posmo Segments is available for everyone and easy to understand. For every duration, you can also upload your screenshot of your Posmo Segment (from the phone or from the web) to Issues (without any privacy implications) and we all can check what made this segment particularly speedy or very slow. 


## Last Meeting: 2. Juli
See Slack



## Interesting Links:
- [Nationales Personenverkehrsmodell](https://www.are.admin.ch/are/de/home/verkehr-und-infrastruktur/grundlagen-und-daten/verkehrsmodellierung/npvm.html)
- [Extracting Patterns from Large Movement Datasets](https://austriaca.at/?arp=0x003b9d88)
