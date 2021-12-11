# XAMPP-MySQL-shutdown-unexpectedly

# Open XAMPP and click start MySQL button and it giving me an error like MySQL Shutdown Unexpectedly

    Please do NOT delete ibdata1 file from the folder ` YoursXamppFolder/mysql/data `

# Instead, first try using the MySQL backup folder which is included with XAMPP. So do the next:
  
    1. Rename the folder mysql/data to mysql/data_old (you can use any name)
    
    2. Create a new folder mysql/data
    
    3. Copy the content that resides in mysql/backup to the new mysql/data folder
    
    4. Copy all your database folders that are in mysql/data_old to mysql/data 
    (skipping the mysql, performance_schema, and phpmyadmin folders from data_old)
    
    5. Finally copy the ibdata1 file from mysql/data_old and replace it inside mysql/data folder
    
    6. Start MySQL from XAMPP control panel
    
    
 # Happy :)  
