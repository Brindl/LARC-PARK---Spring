# LARC-PARK---Spring
Project started 21 Feb 2019.
An attempt at creating a system to detect parking spots and determine how many are available.

__Guidance__

Sudo Code

  * Define variables
    * Repository locations, time, date
    * Array of coordinates for each parking space(Spot 1, x1,y1,x2,y2), type of parking space (standard, handicap, motorcyle)
  
  * While Loop:
    * Declare video frame or photo to analyze next
    * Blur colors to produce larger/more simple shapes
    * Compare each parking spot to empty parking spot data in a predetermined order
      * If same: Parking spot is open (0)
      * If different enough: parking spot is occupied (1)
    * Write array of values to a textfile (Spot 1:Empty/Standard, Spot 2:Filled/Handicap, Spot 3:Filled/Standard)
    * End Loop:
  
  * Interpreting Software
    * Open textfile
    * Display textfile values in a meaningful way
  
Compile Code (Python)
* https://github.com/Brindl/LARC-PARK---Spring/wiki/Generating-a-compiled-executable-(freezing-code)

Call Executable (Interpret Image)
* ~~DetectParking.exe <Video_Filename or Camera_Number> <ParkingData_Filename>~~

Call Executable (Display Data to User)
* Unknown

__References__

  1. A project with similar intent to this project. Uses video feed to detect if pre-mapped parking spaces are still visible.           
      https://github.com/eladj/detectParking
  
      a. Discussion on project to use photos rather than video.
        https://github.com/eladj/detectParking/issues/5#issuecomment-465852213
        
  2. Using deep learning to detect parking spots (Project)
      https://github.com/fabiocarrara/deep-parking

      a. Project it is based on (Project)
        http://cnrpark.it/
        
      b. Deep learning for decentralized parking lot occupancy detection (Paper)
      https://www.sciencedirect.com/science/article/pii/S095741741630598X

  3. Parking Lot Database__
    https://web.inf.ufpr.br/vri/databases/parking-lot-database/
    
  4. Close up car detection using a camera (Each camera detects 5-10 cars. Lots of Cameras)
  https://github.com/DeepParking/DeepParking

  5. App for public parking by city
  https://github.com/kiliankoe/ParkenDD
  
  6. Montreal publicly posts street and parking information
  http://donnees.ville.montreal.qc.ca/dataset/stationnement-sur-rue-signalisation-courant
  
  7. Car Masking
  https://medium.com/@ageitgey/snagging-parking-spaces-with-mask-r-cnn-and-python-955f2231c400
  
__Glossary__
   
   1. https://usabilityetc.com/articles/image-processing-glossary/
