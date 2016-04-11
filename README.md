# clever-devices
### WCF project in CSharp

#### Requirements:
1. **Microsoft Visual Studio**
   * This was developed using Visual Studio Community 2015 (free to download)
   * Installed the following packages through NuGet manager:
     * Unity.Wcf - for dependency injection
     * Dapper - high performance Micro-ORM
2. **Microsoft Sql Server 2018**
   * The three (3) Function in the Database1 project under Function folder should be executed
     * fn_ReverseWords.sql
     * fn_IsPrime.sql
       * hardcoding some values makes it faster
       * using combination of stored procedure calling function makes the codes cleaner and reusable
     * fn_CommnCharacters.sql
   * One (1) Stored procedure in the Databse1 project under Stored Procedure folder should be executed
     * GetPrimeCount.sql

#### Highlights:
1. Use of the latest Visual Studio makes it easier to install packages by using NuGet manager.
2. Use of Unity.Wcf for dependency injection makes it easier to connect to the database.
3. Use of Dapper eliminates Data Access Layer.
