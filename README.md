# clever-devices
### WCF project in CSharp

#### Requirements:
1. **Microsoft Visual Studio**
   * This was developed using Visual Studio Community 2015 (free to download)
   * Installed the following packages through NuGet manager:
     * Unity.Wcf - for depency injection
     * Dapper - high performance Micro-ORM
2. **Microsoft Sql Server 2018**
   * The three (3) Function in the Database1 project under Function folder should be executed.
     * fn_ReverseWords.sql
     * fn_IsPrime.sql
     * fn_CommnCharacters.sql
   * One (1) Stored procedure in the Databse1 project under Stored Procedure folder should be executed.
     * GetPrimeCount.sql
