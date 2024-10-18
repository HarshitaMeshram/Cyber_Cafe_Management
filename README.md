# Cyber_Cafe_Management
Cyber_Cafe_Management_System

freeinformation.ThedatabaseisdrivenbyMySQLthusprovidingportability. 
SOFTWAREANDHARDWARESPECIFICATIONS 
 
HARDWAREREQUIREMENTS: 
 
 
Processor : IntelP-IVbasedsystem 
ProcessorSpeed : 2.0.GHz 
RAM : 1GB 
HardDisk : 40GBto80GB 
 
 
 
 
 
 
SOFTWAREREQUIREMENTS: 
 
 
 
Database : MySQL 
Server : Apache 
Frontend : HTML 
Scriptinglanguage : JavaScript 
IDE : Sublime 
Technology : PHP 
PROJECTOVERVIEW 
 
In Cyber Café Management System we use PHP and MySQL database. This is 
theproject which keeps records of daily users of cyber cafe. Cyber 
CaféManagementSystemhas one modulei.e.admin. 
 
1. Dashboard:Inthissectionadmincanbrieflyviewtotal 
numberofcomputersandtotalnumberofusercomeincybercafe. 
2. Computer:Inthissection,admincanmanagethecomputers(add/update). 
3. Users:Inthissection,admincan addnewusers,update 
outime,priceandremarks, andviewdetailsofold users. 
4. Search: Inthissection admincansearch usersonthebasisofentryid. 
5. Report: Inthissection admincanviewnumberof userscomesincyber 
caféinparticularperiods. 
6. Profile:Inthissectionadmincanupdatehis/herprofile. 
7. ChangePassword:Inthissectionadmincanchangehis/herpasswords 
8. Logout:Throughthisbuttonadmincanlogout. 
Admincanalso recoverhis/herpassword. 
Note:InthisprojectMD5encryptionmethodused. 
SYSTEMDEVELOPMENTENVIRONMENT 
 
 
 
1. HTML 
WHATISHTML? 
 
To publish information for global distribution, one needs a university
understoodlanguage, a kind of publishing mother tongue that all computers may 
potentiallyunderstand.ThepublishinglanguageusedbytheWorldWideWebisHTML(
 HyperTextMarkupLanguage) 
 
 
HTMLGivesAuthorstheMeansTo 
 
1. Publishonlinedocumentswithheadings,text,tables,list,photosetc. 
2. Retrieveonlineinformationviahypertextlinks,attheclickofabutton 
3. Designformsforconductingtransactionswithremoteservices,foruseinsearching
 information,makingreservation,orderingproductsetc.; 
4. Includesspreadsheets,videoclips,soundclips,andotherapplicationsdirectl
 y inthedocuments. 
5. 
SomeHTMLTags 
 
 
<HTML> :StartinganHTMLtag 
 
<HEAD> : Creating awebpage’shead 
 
<TITLE> : Givingawebpage ‘sbody 
 
 
</HEAD> : Endingawebpages head 
</BODY> :Endingaweb pages body 
 
</HTML> :Endingaweb page 
 
<FORM> : CreatingaHTMLforms 
 
<INPUTTYPE=BUTTON> :Creatingabuttons 
 
<INPUTTYPE=CHECKBOX>:Creatingacheckboxes 
 
<INPUTTYPE=SUBMIT> : Creating asubmitbutton 
 
<INPUTTYPE=TEXT> :Creatingatext fields 
 
 
HTML4.0 
 
HTML 4.0 extends with mechanisms for style sheets, scripting, frames 
embeddingobjects, improved support for right to left and mixed direction texts, 
richer 
tablesandenhancementstoform,offeringimprovedaccessibilitiesforpeoplewithdisabil
 ity. 
 
 
2. INTRODUCTIONTOJAVASCRIPT
 WHATISJAVASCRIPT? 
JavaScript, originally supported by Netscape Navigator, is the most popular 
Webscripting language today. JavaScript lets you embed programs right in your 
Webpages and run these programs using the Web browser. You place these 
programs 
ina<SCRIPT>element.IfyouwantthescripttowritedirectlytotheWebpage,placeitin 
the <BODY>element. 
 
 
EX:<HTML> 
 
<HEAD> 
 
<TITLE></TITLE> 
</HEAD> 
 
<BODY> 
 
<SCRIPTLANGUAGE=”JavaScript”> 
 
</SCRIPT> 
 
</BODY></HTML> 
 
 
JAVASCRIPTSOBJECTS 
 
JavaScriptisanobject-orientedlanguage.JavaScriptcomeswithanumberofpredefinedobjects. 
ObjectsoftheJavaScript 
 
1. Document: Corresponds to the current Web page’s body. Using this 
object,youhaveaccesstotheHTMLofthepageitself,includingthealllinks,images
 and anchorsin it. 
2. Form:HoldsinformationaboutHTMLformsinthecurrentpage. 
3. Frame:Refersto aframeinthebrowser’swindow. 
4. History:Holdstherecordsof sitesthe Webbrowserhasvisitedbeforereachingthe 
currentpage. 
5. Location:Holdsinformationaboutthelocationofthecurrentwebpage. 
6. Navigator: Refers to the browser itself, letting you determine what 
browsertheuserhas. 
7. Window:Referstothecurrentbrowserwindow. 
 
 
JAVASCRIPTSEVENTS 
 
SomeoftheeventsofJavaScript 
 
1. onChange:Occurs whendatainacontrol,likeatext field,changes. 
2. onClick:Occurswhenanelement isclicked. 
3. onFocus:Occurswhenanelementgetsthefocus. 
4. onMouseDown: Occurswhenamousebuttongoesdown. 
5. onReset:Occurswhentheuserclickstheresetbutton. 
 
 
JAVASCRIPTSFUNCTIONS 
 
 
Declarationoffunction 
 
Syntax:functionfunctionname() 
 
{ 
 
… 
 
… 
 
} 
 
 
 
Writethesefunctionsin<SCRIPT>tag. 
 
 
 
 
 
 
5. RDBMSCONCEPTS 
 
1. DATAABSTRACTION 
 
A major purpose of a database system is to provide users with an abstract 
viewof the data. This system hides certain details of how the data is stored 
andmaintained.Howeverinorderforthesystemtobeusable,datamustberetrievedeffi
 ciently. The efficiency lead to the design of complex data 
structurefortherepresentationofdatainthedatabase.  Certaincomplexitymustbe 
hiddenfromthedatabasesystemusers.Thisaccomplishedbydefiningseverallevelsofa
 bstractionatwhichthedatabasemaybe viewed. 
2. CLASSIFICATIONOFDATABASE 
 
Thereare3typesofdatabaseapproaches givenbelow, 
 
a. HierarchicalDatabase: 
 
In this type of model data is represented in simple tree structured. 
Therecord at the top of three is known as root, the root may have 
anynumberofdependents.Eachofthesemayhaveanynumberoflow 
leveldependentsand soonupto any numberoflevels.The 
disadvantagesof the approach are that noindependentrecord 
occurrencecanexistwithoutit’ssuperior. 
 
b. NetworkDatabase: 
 
InaNetworkdatabase,dataisrepresentedbyNetworkstructure.Inthisappro
 ach record occurrence can have any number of superiors as wellas any 
number of immediate dependents thus allow manyto 
manycorrespondencedirectlythananhierarchicalapproach.Themaindisa
 dvantageoftheNetworkmodelisdatarepresentationisverycomplexresulti
 ngincomplexityoftheDML(DataManipulationLanguage). 
c. RelationalDatabase: 
 
The Relational model represents data and relationships among data 
bya collection of tables each of which has a number of columns 
withuniquenames. 
 
6. THESQLLANGUAGE 
SQLisalanguageforrelationaldatabase.SQLisanon-procedurali.e.,whenweuse SQLwe 
specifywhatwe wanttobe done nothowtodoit. 
FeaturesofSQL 
 
1. SQLisaninteractivequerylanguage. 
2. SQLisadatabaseadministrationlanguage. 
3. SQLisadatabaseprogramminglanguage. 
4. SQLisaclient/serverlanguage. 
5. SQLisadistributeddatabaselanguage. 
6. SQLis adatabasegatewaylanguage. 
 
 
BasicSQLCommands 
 
 
✓ DataDefinitionLanguagecommands(DDL) 
 
✓ DataManipulationLanguagecommands(DML) 
 
✓ TransactionControlLanguagecommands(TCL) 
 
✓ DatacontrolLanguagecommands(DCL) 
 
PHP 
 
• PHPisanacronymfor"PHP:HypertextPreprocessor" 
• PHPisawidely-used,opensourcescriptinglanguage 
• PHPscriptsareexecutedon theserver 
• PHPisfree todownloadanduse 
 
Whatisa PHPFile? 
 
• PHPfilescancontaintext,HTML,CSS,JavaScript,andPHPcode 
• PHPcodeare executedontheserver,andtheresultisreturnedto 
thebrowserasplainHTML 
• PHPfileshaveextension".php" 
 
WhatCanPHPDo? 
• PHPcangeneratedynamicpagecontent 
• PHPcancreate,open,read,write, delete,andclose filesonthe server 
• PHPcancollect formdata 
• PHPcansendand receivecookies 
• PHPcanadd,delete,modifydatainyourdatabase 
• PHPcanbeusedtocontroluser-access 
• PHPcanencrypt data 
 
WithPHPyouarenot limitedtooutputHTML.Youcanoutput 
images,PDFfiles,andevenFlashmovies.Youcanalsooutputany 
text,suchasXHTMLandXML. 
DATAFLOWS 
Process:Atransactionofinformation thatresideswithinthebounds 
ofthe system tobe module. 
DESIGNDOCUMENT 
 
 
• The entire system is projected with a physical diagram which specifics 
theactual storage parameters that are physically necessary for any database 
tobestored on to the disk. Theoverallsystemsexistentialidea is 
derivedfromthisdiagram. 
 
• TherelationuponthesystemisstructurethroughaconceptualER
Diagram,whichnotonlyspecificstheexistentialentitiesbutalsothestandardrelat
 ionsthroughwhichthesystemexistsandthecardinalitiesthat are 
necessaryforthesystemstate tocontinue. 
 
• The content level DFD is provided to have an idea of the functional 
inputsand outputs that are achieved through the system. The system depicts 
theinputandoutputstandardsatthehighlevelofthe systemsexistence. 
 
ADFDdoesnotshowasequenceofsteps.ADFDonlyshowswhatthedifferentprocessin 
asystemisandwhatdataflowsbetween them. 
Thefollowing aresomeDFDsymbolsusedintheproject 
 
Externalentities 
 
 
 
 
 
 
 
 
 
DATASTORE: A repository of data that is to 
bestored for use by one or more processes, may be 
assimple as buffer of queue or as a 
relationaldatabase. 
 
 
RULESFOR DFD: 
 
 
• Fixthescopeofthesystembymeans ofcontextdiagrams. 
• OrganizetheDFDsothatthemainsequenceoftheactionsreadslefttorightand 
top to bottom. 
• Identifyallinputsandoutputs. 
• Identifyandlabeleachprocess internaltothesystemwithroundedcircles. 
• Aprocessisrequiredforallthedatatransformationandtransfers.Therefore, 
never connect a data store to a data source or the destinations 
oranotherdatastorewith justadataflowarrow. 
• Donotindicatehardwareandignorecontrolinformation. 
• Makesurethenamesoftheprocessesaccuratelyconveyeverythingtheprocessis
 done. 
• Theremustnotbeunnamedprocess. 
• Indicateexternalsources anddestinations ofthedata,withsquares. 
• Numbereachoccurrenceofrepeatedexternalentities. 
• Identifyalldataflowsforeachprocessstep,exceptsimpleRecordretrieval
 s. 
• Labeldataflowoneacharrow. 
• Usedetailsflowoneacharrow. 
• Usethedetailsflow arrowtoindicatedatamovements. 
• Therecan’tbeunnameddataflow. 
• Adataflow can’tconnecttwoexternalentities. 
LEVELSOFDFD: 
 
 
Thecomplexityofthebusinesssystemmeansthatitisaresponsibletorepresenttheoperationsof any 
system of single data flow diagram. At the top level, an Overview of the different systemsin an 
organization is shown by the way of context analysis diagram. When exploded into 
DFDTheyarerepresented by: 
• LEVEL-0:SYSTEMINPUT/OUTPUT 
• LEVEL-1:SUBSYSTEMLEVELDATAFLOWFUNCTIONAL 
 
 
0.0 
 
CyberCafeManagement
 System Admin 
• LEVEL-2:FILELEVELDETAILDATAFLOW. 
Theinputandoutputdatashown shouldbeconsistentfromoneleveltothenext. 
 
 
LEVEL-0: SYSTEMINPUT/OUTPUTLEVEL 
A level-0 DFD describes the system-wide boundaries, dealing inputs to and outputs 
fromthe system and major processes. This diagram is similar to the combined user-level 
contextdiagram. 
 
LEVEL-1: SUBSYSTEMLEVELDATAFLOW 
Alevel
1DFDdescribesthenextlevelofdetailswithinthesystem,detailingthedataflowsbetweensubsystems, 
which makeup thewhole. 
 

1.2 
 
Admin 
Admin 
2. UnifiedModelingLanguageDiagrams(UML): 
 
• The unified modeling language allows the software engineer to express 
ananalysis model using the modeling notation that is governed by a set 
ofsyntacticsemantic andpragmaticrules. 
• A UML system is represented using five different views that describe 
thesystem from distinctly different perspective. Each view is defined by a set 
ofdiagram, whichisasfollows. 
UserModelView 
 
i. Thisviewrepresentsthesystemfromtheusersperspective. 
 
ii. Theanalysisrepresentationdescribesausagescenariofromtheend
usersperspective. 
Structuralmodelview 
 
◆ Inthis modelthe dataandfunctionalityarearrivedfrominsidethesystem. 
 
◆ Thismodelviewmodelsthestaticstructures. 
 
BehavioralModelView 
 
◆ It represents the dynamic of behavioral as parts of the system, 
depictingtheinteractionsofcollectionbetweenvariousstructuralelementsdes
 cribedintheusermodelandstructuralmodelview. 
ImplementationModelView 
 
◆ In this the structural and behavioral as parts of the system are 
representedastheyaretobe built. 
EnvironmentalModelView 
Inthisthestructuralandbehavioralaspectsoftheenvironmentinwhichthesystemistobe 
implementedarerepresented. 
UMLisspecificallyconstructedthroughtwodifferentdomainstheyare 
◆  UMLAnalysismodeling,whichfocusesontheusermodelandstruc
 tural modelviewsofthe system? 
◆  UML design modeling, which focuses on the behavioral 
modeling,implementation modelingandenvironmentalmodelviews. 
 
 
  Linerepresents flow 
Structured analysis is a set of tools and techniques that the 
analyst.Todevelop anewkind ofasystem: 
The traditional approach focuses on the cost benefit and feasibility analysis, 
Projectmanagement,andhardware andsoftwareselection apersonalconsiderations. 
 
DATABASEDESIGN 
The data in the system has to be stored and retrieved from database. Designing 
thedatabaseispartofsystemdesign.Dataelementsanddatastructurestobestoredhavebee
 n identified atanalysisstage. Theyare 
structuredandputtogethertodesignthedatastorageand retrievalsystem. 
A database is a collection of interrelated data stored with minimum redundancy 
toserve many users quickly and efficiently. The general objective is to make 
databaseaccesseasy,quick,inexpensiveandflexiblefortheuser.Relationshipsareestablis
 hedbetweenthedataitemsandunnecessarydataitemsareremoved.Normalization is 
done to get an internal consistency of data and to have minimumredundancy and 
maximum stability. This ensures minimizing data storage required,minimizing 
chances of data inconsistencies and optimizing for updates. The 
MSAccessdatabasehasbeenchosenfordevelopingtherelevantdatabases. 
Cyber Cafe Management System Project (CCMS) contains 3 MySQL tables 
:tblusertableStructure:Thistablestoretheloginandpersonaldetailsofuser. 
 
tblcomputerstableStructure:Thistablestorethecomputerandcabindetails. 
 
 
 
tbluserstableStructure:Thistablestoretheuserpersonalandcomputerusagedetails. 
 
SOFTWARETESTINGTECHNIQUES: 
 
Softwaretestingisacriticalelement ofsoftwarequalityassuranceandrepresents the 
ultimate review of specification, designing and 
coding.TESTINGOBJECTIVES: 
1. Testingisprocessofexecutingaprogramwiththeintent of findinganerror. 
 
2. Agoodtestcasedesignisonethathasaprobabilityoffinding 
anasyetundiscoverederror. 
3. A successful test is one that uncovers an as yet undiscovered 
error.These aboveobjectives implyadramaticchangeinviewport. 
Testingcannotshowtheabsenceofdefects,itcanonlyshowthatsoftwareerrorsarepre
 sent. 
Therearethreetypes oftestingstrategies 
 
 
1. Unittest 
2. Integrationtest 
3. Performancetest 
UnitTesting: 
Unit testing focuses verification efforts on the smallest unit of software 
designmodule.Theunittestisalwayswhiteboxoriented.Theteststhatoccuraspartofu
 nittestingaretestingthemoduleinterface,examiningthelocaldatastructures, testing 
the boundary conditions, execution all the independent pathsandtestingerror
handlingpaths. 
 
IntegrationTesting: 
 
 
Integrationtestingisasystematictechniqueorconstructiontheprogramstructurewhil
 eatthesametimeconductingteststouncovererrorsassociatedwithinterfacing. Scope 
of testing summarizes the specific functional, performance,and internal design 
characteristics that are to be tested. It employs top-downtestingandbottom
uptesting methods forthis case. 
 
PerformanceTesting: 
 
 
Timing for both read and update transactions should be gathered to 
determinewhethersystemfunctions arebeing performedinan 
acceptabletimeframe. 
