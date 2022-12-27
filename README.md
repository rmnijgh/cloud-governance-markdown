# AWS Well-Architected Framework
Het AWS Well-Architected Framework is een reeks best practices en richtlijnen voor het ontwerpen, bouwen en beheren van
cloud systemen op het AWS cloudplatform. Het is ontworpen om organisaties te helpen veilige en
efficiente systemen te bouwen die voldoen aan de behoeften van hun klanten.

Cloud governance is een belangrijk aspect van het AWS Well-Architected Framework, omdat het organisaties helpt ervoor te zorgen
dat hun cloud resources is afgestemd op hun bedrijfsdoelstellingen en dat deze op een consistente, betrouwbare en
kosteneffectieve gebruikt worden. 

AWS Well-Architected Framework bevat uit 5 pilaren:
- Operational Excellence 
- Security
- Reliability
- Performance Efficiency 
- Cost Optimization


## Operational Excellence
Operational Excellence verwijst naar de mogelijkheid van een organisatie om haar
infrastructuur en resources op een betrouwbare, efficiënte en veilige manier uit te voeren en te controleren.

Operational Excellence is een cruciaal aspect van elk goed ontworpen systeem, omdat het ervoor zorgt dat de organisatie hun
systemen en applicaties betrouwbaar en efficiënte kan laten draaien. Door prioriteit te geven aan Operational Excellence, kunnen
organisaties de downtime verminderen, prestaties verbeteren en ervoor zorgen dat hun systemen en gegevens veilig zijn.


## Security
In de context van cloud governance speelt de Security pillar een belangerijke rol bij het handhaven van een veilige
bedrijfsomgeving in de cloud. Dit omvat de implementatie van controles, en het waarborgen van rechten & permissies binnen de users in jou cloudomgeving. Ook het naleven van wetten en standaarden is een belangerijk aandachtspunt voor governance.

Belangerijke componenten van de Security pillar zijn:
- Identity and Access Management (IAM): Deze service bied de mogelijkheid om rechten en permissies te delegeren over gebruikers en groepen. Binnen cloud governance levert dit naleving op van eventuele security policies.
- Encryption: Hiermee is het mogelijk om gevoelige data te versleutelen. Dit kan door encryption in transit of encryption at rest. 
- Compliance: Het belangerijk binnen Cloud governance om standaarden, certificaten en wetten na te leven welke voor jou organisaite van toepassing is. Binnen de security pillar van AWS word aanbevolen om deze standaarden na te leven doormiddel van AWS Artifact.
- Monitoring en Logging: Het is voor Cloud governance van belang om je beveiliging goed te monitoren en de logs lang te bewaren. Met deze informatie is het mogelijk om security audits uit te voeren.


## Reliability
De Reliability pillar zorgt ervoor dat systemen zichzelf snel kunnen herstellen, en een hoge beschikbaarheid kunnen halen.
Omdit te kunnen bereiken stelt de richtlijn veel controles en waarborgen voor om downtime te voorkomen.

Deze controles en waarborgen bieden als volgt:
- High availability: Doormiddel van EC2 Auto scaling en Elastic load balancers is het mogelijk om capaciteit en verdeling te waarborgen tussen meerdere availability zones en regions. 
- Disaster recovery: Door het maken van backups, en het inrichten en bouwen van een disaster recovery plan. Waarborg je de 
mogelijkheid om snel te kunnen herstellen indien dit nodig is.
- Alerting: Doormiddel van Alerting via Cloudwatch, kun je bij alerts met betrekking tot storingen verdere automatisering bouwen om de beschikbaarheid van je cloud omgeving te herstellen.

Door het volgen van de Reliability Pillar zorg je ervoor dat je systemen beschikbaar staan. En dat je systemen snel en
makkelijk herstellen van storingen en disrupties. Hiermee verminder je de downtime en verbeter je de betrouwbaarheid van je
cloud omgeving.


## Performance Efficiency
Performance Efficiency bied richtlijnen en een reeks best practices voor het ontwerpen van betrouwbare, efficiënte en
kosteneffectieve systemen in jou cloud omgeving. Het doelt naar het optimaliseren van de prestaties van je systemen, terwijl de
kosten tot een minimum worden beperkt.

Gebruik van resources, kostenpotimalisatie en prestatieoptimalisatie zijn de belangerijkste kenmerken van deze richtlijn.
Hierbij is het van belang dat alle resources die je gebruikt zo veel mogelijk gebruikt worden zodat je hiermee de beste kosten in verhouding met de prestaties kan hebben.

Verschillende diensten binnen AWS kunnen hierbij helpen zoals EC2 Spot instances en reserveringen van EC2 instances.


## Cost Optimization
In de Cost Optimization pillar bevinden zich richtlijnen die doelen op het efficiënt gebruik maken van je kosten, en deze waar mogelijk te verminderen.
Cost Optimization zorgt ervoor dat u de waarde van uw cloud-investeringen verhoogt en tegelijkertijd de kosten zo klein mogelijk houdt.
Dit houdt in dat controles en waarborgen gebruikt moeten worden om de kosten te optimaliseren en onnodige uitgaven te minimaliseren, en toch de prestatie- en betrouwbaarheidseisen van uw systemen wordt voldaan.


## Bibliografie
- The Five Pillars of the Framework - AWS Well-Architected Framework. (n.d.). https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillars.wa-pillars.en.html


