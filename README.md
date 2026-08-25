# VDV301CZ V2.3CZ1.0

This is modified version of VDV301 for usage in Czech Republic, especially for Prague Integrated Transport. Its development is in beta stage at the moment, created to satisfy contemporary needs of PID, ready to accept new propositions.
All the changes are to be slowly proposed and merged into official/mainline VDV301.
The documentation is available in Czech at the moment.

### Graphic design manual for passenger information systems
* https://pid.cz/wp-content/uploads/system/sk_bus/SK_bus_priloha_odbavovaci_a_informacni_zarizeni_2024-12-01.pdf

### Weblinks to original VDV301

* https://www.vdv.de - Verband Deutscher Verkehrsunternehmen e.V. (VDV)
* https://www.vdv.de/ip-kom-oev.aspx - Internet Protokoll basierte Kommunikationsdienste im ÖV (IP-KOM-ÖV)
* https://forum.vdv.de - Bulletin board for companies and other parties interested in VDV 301


## Changelog
- 20260825_1629
  - RemoteControlService XSD file rename 
  
- 20260822_1859
  - RemoteControlService concept
  
- 20260822_1603
  - TicketValidationService XSD now bound to 2.3CZ1.0 enumerations and common xsd

- 20250626_1719
  - readme headline change
  - fixed link to a PDF

- 20250626_1719
  - removed fareZoneChange from IBIS-IP_common_V2.3CZ1.0.xsd

- 20241205_1505
  - deleted outdate demo XML files
  - IBIS-IP_common_V2.3CZ1.0.xsd
    -  added GlobalStopRef to StopPoint

- 20241204
  - IBIS-IP_CustomerInformationService_V2.3CZ1.0.xsd
    - added required elements comments 
  - IBIS-IP_common_V2.3CZ1.0.xsd
    - added required elements comments 
      - DisplayContentStructure
        - RunNumber changed type to InternationalTextType (used for display)
      - TripInformationStructure
        - RunNumber changed type to IBIS-IP.string (used for data pairing, to allow for rootLine_order pattern)
  - IBIS-IP_Enumerations_V2.3CZ1.0.xsd
    - added trolleybus submode      
  - deleted outdated .docx documentation

- 20241103
  - added fareZoneChange to IBIS-IP_common_V2.3CZ1.0.xsd

- 20241110
  - rename XSD files to 2.3CZ1.0 version
  
- 20240907
  - initial commit of 2.3CZ1.0 version