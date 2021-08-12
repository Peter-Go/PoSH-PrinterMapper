# PrinterMapper
v1 of a windows printer mapper I created in Powershell. The printserver name and shared printers are hard coded in so it was more of a learning experience rather then a released product.

v2 makes use of get-printer and get-printconfiguration to dynamically list the printers and their capabilities. The print server is hard coded in for now as searching using Get-ADObject for print queues would take additional time in using the application.
