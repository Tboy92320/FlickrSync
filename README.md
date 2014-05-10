FlickrSync
==========

FlickrSync tool from CodePlex (https://flickrsync.codeplex.com/) with improvements to speed and reliability for my own use.

Others are welcome to re-use or contribute

HOW TO
==========
 * USE

  Create a Flickr account.
  
  Launch FlickrSync and setup it 
  
  Schedule synchronization launching this command :
  
   FlickrSync.exe /noauto

 * CONTRIBUTE
 
  Correct bugs

  Add new features (backup video)
  
  Create an automatic build to generate a Windows setup

 * BUILD

  Install .Net Framework 

  Download SharpDevelop (http://www.icsharpcode.net/OpenSource/SD/Default.aspx)

RELEASES
==========
  * 0.9.0.1 Add feature : Synchronize children folders of selected folder 
  
  * 0.9.0.0 Migration
  
    Migration to SharpDevelop

    Migration to .Net Framework 3.5
    
    Create 'noauto' mode in command line to schedule synchronization
    
    Some performance improvements
    
      Limit the number of uploaded Items by session ('ItemLimit' in app.config)
      
      Disable image thumb (memory usage)
      
      ...