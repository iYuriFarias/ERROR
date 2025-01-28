# ERROR
Open Error LASER GRBL


LaserGrbl v7.14.0.0
TypeOf exception  [System.TypeInitializationException]
Exception message [The type initializer for 'LaserGRBL.UsageStats' threw an exception.]
Exception source  [LaserGRBL], thread []
Exception method  [Void LoadFile()]

   ----------- stack trace -----------
   at LaserGRBL.UsageStats.LoadFile()
   at LaserGRBL.Program.Main(String[] args)

Inner exception data
TypeOf exception  [System.TypeInitializationException]
Exception message [The type initializer for 'LaserGRBL.GrblCore' threw an exception.]
Exception source  [LaserGRBL], thread []
Exception method  [LaserGRBL.GrblConfST get_Configuration()]

   ----------- stack trace -----------
   at LaserGRBL.GrblCore.get_Configuration()
   at LaserGRBL.ExceptionManager.CreateAndShow(Exception ex, Boolean cancontinue, Boolean manual)

Inner exception data
TypeOf exception  [System.IO.FileNotFoundException]
Exception message []
Exception source  [LaserGRBL], thread []
Exception method  [LaserGRBL.PSHelper.MaterialDB Load()]

   ----------- stack trace -----------
   at LaserGRBL.PSHelper.MaterialDB.Load()
   at LaserGRBL.GrblCore..cctor()

HELP ME PLEASE!


