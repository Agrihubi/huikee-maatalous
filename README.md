# Huikee maatalous

Kokoelma maataolouden dataan ja koodiin liittyviä linkkejä: githubin awesome-kokoelmien hengessä, Suomi-keskeisesti.

Puuttuuko jotain oleellista? Tarviiko korjauksia? Lähetä muokkauspyyntö joko viestien/issueiden kautta tai suoraan pull-requestina. 

Listausta tehdään osana [IFDEA-hankkeen](https://www.tuni.fi/fi/tutkimus/ifdea) (2021-2023) tavoitteita.

# Käytäntöyhteisö

Paikkoja ja nettialustoja, joissa avointa työskentelyä ja keskustelua tämän aihepiirin ympärillä tapahtuu. Yhteistyö ja sen työkalut hakevat yhä muotoaan, ja tekijät ovat toistaiseksi melko hajallaan.

* Agrihubi Github https://github.com/Agrihubi - Tämä Git-repository. Lähinnä linkkihakemisto toistaiseksi. 
* Agri Data Finland - Keskustelua Discord-alustalla: https://discord.gg/p5quCj3g6R
* Maaseutuverkosto/Agrihubi verkkosivuso https://maaseutuverkosto.fi/ - Tapahtumakalenteri, keskustelufoorumi
* Some-tageja (Mastodon, Twitter, yms): #AgriHubi, #AgriData (mitä muita?) - Etsi tai käytä, jos haluat löytää tai tulla löydetyksi.


# Data, rajapinnat

* Paituli,  on paikkatietoaineistojen lataus- ja rajapintapalvelu, https://paituli.csc.fi/
* Luonnonvarakeskus - datasettejä ja rajapintoja
  * https://opendata.luke.fi/dataset 
  * https://luonnonvaratieto.luke.fi/etusivu
  * https://statdb.luke.fi - tilastotietokanta
  * https://px.luke.fi/PxWeb/pxweb/fi/ - tutkimustulostietokannat

* SYKEn avoimet rajapinnat, https://www.syke.fi/fi-FI/Avoin_tieto/Avoimet_rajapinnat ja aineistot https://www.syke.fi/fi-FI/Avoin_tieto/Paikkatietoaineistot/Ladattavat_paikkatietoaineistot ja karttpalvelut https://www.syke.fi/fi-FI/Avoin_tieto/Karttapalvelut
* Ruokavirasto - Paikkatietoaineistot - mm. pelto- ja kasvulohkot [https://www.ruokavirasto.fi/tietoa-meista/avointieto/inspire/](https://www.ruokavirasto.fi/tietoa-meista/avointieto/paikkatietoaineistot/)
* Kasvinsuojeluaineet -  https://www.avoindata.fi/data/fi/dataset/kasvinsuojeluaineet
* Maatalous, kalastus, metsätalous ja elintarvikkeet -ryhmä avoindata.fi -palvelussa - https://www.avoindata.fi/data/fi/group/maatalous-kalastus-metsatalous-ja-elintarvikkeet
## Säätieto:

* FMI - ilmatieteen laitos
  * https://en.ilmatieteenlaitos.fi/open-data-manual
  * Säähavaintojen lataus - https://www.ilmatieteenlaitos.fi/havaintojen-lataus
  * FMI GitHubissa - https://github.com/fmidev
  * FMI datojen valmiita parsinta koodeja, https://github.com/pnuu/fmiopendata
* https://github.com/GiorgioBalestrieri/cams_radiation_python - A Python client for the CAMS radiation service.
* https://openweathermap.org/

## EU-data

* https://agri4cast.jrc.ec.europa.eu/DataPortal/Index.aspx - Agri4cast resources portal. 
* https://www.ecmwf.int/ - European Centre for Medium-Range Weather Forecasts.
* https://esdac.jrc.ec.europa.eu/ - European soil data centre
* 

## Satelliitti:
* https://www.sentinel-hub.com/ - Sentinel Hub
  * Sentinel hub client software etc, https://github.com/sentinel-hub
  * https://github.com/sentinel-hub/eo-learn - Earth observation processing framework for machine learning in Python
* https://github.com/ollinevalainen/satellitetools - Python client, pelto-observatorin satellittihaut google earthista

## Datakuvaukset & sanastot
Listaus eri datakuvaus-standardeista tai avoimista menetelmistä, joiden avulla määritellään datan rakenteita ja kenttien määrittelyjä. Esimerkiksi Isobus ja AgGateway. 
* Sanastoja ja käsitteistöjä
 - AGROVOC Multilingual Thesaurus - https://agrovoc.fao.org/browse/agrovoc/en/
 - Suomalainen sanastopalvelu, https://finto.fi/fi/, esim. yso yleinen sanasto; https://finto.fi/yso/fi/
 - SKOSMOS, vocabulary and SPARQL tool, https://github.com/NatLibFi/Skosmos
 - The NAL Agricultural Thesaurus, https://lod.nal.usda.gov/nalt/en/
 - Agrisemantics Map of Standards - https://vest.agrisemantics.org/
 - The International Consortium for Agricultural Systems Applications (ICASA) Vocabulary - https://agmip.github.io/ICASA.html
 - DEMETER Agriculture Information Model - https://agroportal.lirmm.fr/ontologies/DEMETER-AIM/?p=classes
 - Open Geospatial Consortium, Agricultural Information Model (OGC-AIM) - https://www.ogc.org/press-release/ogc-forms-new-agriculture-information-model-standards-working-group/
* AgGateway - Adapt 
  - https://www.aggateway.org/GetConnected/ADAPT(inter-operability).aspx
  - https://github.com/ADAPT/ADAPT
* inspire
  - INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines - https://inspire.ec.europa.eu/id/document/tg/af
  - https://github.com/INSPIRE-MIF/
* Esimerkkejä 
  * Pelto-observatiorion (json-)skeemakuvauksia - https://github.com/hamk-uas/fieldobservatory-data-schemas
  * Excel forms for field vegetation observations / Peltokasvuston Excel-havaintolomakkeet - https://github.com/hamk-uas/field-vegetation-observations

  
# Koodi

## Alustat

* https://www.oskari.org/ - Oskari map application platform. Avoimen lähdekoodin paikkatietoalusta. Esim paikkatietoikkuna pohjautuu tähän.
* Gaia-x https://gitlab.com/gaia-x
* IDS, https://github.com/International-Data-Spaces-Association/IDS-RAM_4_0
* data, https://bitbucket.org/peltodata/, tulossa  https://github.com/tuni-agri
* Geonetworks, Metatiedon hallinta, https://github.com/geonetwork/core-geonetwork
* farmOS - Web-based farm management and recordkeeping, https://github.com/farmOS
* QField, https://github.com/opengisch/QField
* Microsoft farmbeats, https://learn.microsoft.com/en-us/azure/industry/agriculture/install-azure-farmbeats, https://github.com/microsoft/farmvibes-ai
* Digital Twin Farm, https://www.jamk.fi/en/project/finnish-future-farm


## Lidar 

* Cloud Compare, https://github.com/CloudCompare/CloudCompare - 3D point cloud (and triangular mesh) processing software. 


## Ajo-opastin:

* AgOpenGPS, https://github.com/farmerbriantee/AgOpenGPS
* Esityskalvot AgOpenGPS- ja RTK -aiheista, https://github.com/petrilinna/agopengps


## Analysointityökaluja:

* Whitebox-tools, https://github.com/jblindsay/whitebox-tools
* QGIS, https://github.com/qgis/QGIS



Maaperä-, vesi- ja kasvimallit:
* AquaCrop,  https://github.com/aquacropos/aquacrop
* Python Crop Simulation Environment - PCSE, https://github.com/ajwdewit/pcse
* 

# Data-infrastruktuuri

* Datanvälityspalvelu; https://tritom.com/essential/, https://tritom.com/
* https://gitlab.com/gaia-x/data-infrastructure-federation-services
* https://www.gxfs.eu/ - Gaia-X Federation Services
* https://testbed.fi/

# Palvelut

* https://kartta.paikkatietoikkuna.fi/ - Kansallinen paikkatietoportaali, joka esittelee paikkatietoaineistoja ja -palveluja sekä niiden hyödyntämismahdollisuuksia.
* https://www.vesi.fi/ - Vesi.fi on vesiaiheisen tutkitun tiedon lähde,
* https://agrirouter.com/- With your individual agrirouter you can connect your agricultural machinery, no matter what brand, with many agricultural software solutions.
* Pelto-observatorio
  * https://www.fieldobservatory.org/fi/online-field-data-fi/ - Pelto-observatorio, mittauksia tutkimuspelloilla olevilta sensoreilta ja satelliiteista, Carbon action -hankkeessa kehitetty.
  * Artikkeli: Towards agricultural soil carbon monitoring, reporting, and verification through the Field Observatory Network (FiON) - https://doi.org/10.5194/gi-11-93-2022
  * https://github.com/hamk-uas/fieldobservatory-data-schemas - Pelto-observatiorion (json-)skeemakuvauksia
* https://peltodata.fi/ - Peltodata-palvelu, prototyyppi- ja kehitysalusta, Tampereen yliopiston maataloushankkeet.
* 

# Projektit yms

* https://github.com/TwinYields - Code related to research project: TwinYields - Digital Twin for Supporting Smart Farming Operations. From Luke. 


# Toimijat

* https://github.com/FinLiveRI - Finnish Livestock Research Institute GitHub
* https://github.com/hamk-uas - HAMK Häme University of Applied Sciences 
* https://github.com/tuni-agri - Maataloustutkimus, Tampereen yliopisto, Pori
* https://github.com/lukefi - Natural Resources Institute Finland (Luonnonvarakeskus) 
* https://avointieto.ruokavirasto.fi/ - Ruokavirasto, avoin data

# Artikkeleita, raportteja, opinnäytetöitä yms.

* Towards agricultural soil carbon monitoring, reporting, and verification through the Field Observatory Network (FiON) - https://doi.org/10.5194/gi-11-93-2022
* Ohjelmistokeskeinen automaatio peltojen vesitalouden hallinnassa - https://www.theseus.fi/handle/10024/795901 - https://github.com/raisiope/SSK/
* Älymaatilan datavaraston visualisointi https://www.theseus.fi/handle/10024/790310

# Muita repo-kokoelmia:

* https://github.com/brycejohnston/awesome-agriculture
* https://github.com/chrieke/awesome-geospatial-companies


