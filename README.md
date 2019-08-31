# SCRAPER

> A python tool for cleaning up redundant files in a file system managed by a database

## INTRODUCTION

This tools cleans up your file system by checking file system files against a databases' records.
This is useful in a situation where you have a large database with a file system that might contain files that where part of the system but are now longer needed since they have been deleted from the database but might remain in the file system.
Scraper is a SysAdmin tool that connects to your MySQL database and checks for specific records to clean up your file system.

## DEPENDENCY

Requires mysql.connector module to work with the database.

## CONCLUSION

This tool is still under development, for any queries and contributions. Contact [Arthur Kalikiti](mailto:arthur@kalikiti.net)