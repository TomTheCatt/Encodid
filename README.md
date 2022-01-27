# Encodid
The source code for `Encodid` can be found [here](https://github.com/TomTheCatt/Encodid-Source). `Encodid` is designed to encrypt data that is impossible to decrypt unless the proper key is given. This key can be changed and shared with billions of possible combinations.

For refrence, the possible combinations for each character without duplicates is:
```
41163733193761229359188786791143963213430784
```
The possible combinations for an entire key without duplicates is:
```
98495512350750977829276275697096600021811232494966406779685431480566759258296532253789717847641280604984213851730697723301573704786818007839068160482662200962440710171421533260115447190210524717334316940312580011011366272399936396155952404336882913897351203690964726048606116962399444025673728944558855469635471636702018702264279663040648082944751038947088958467491215123363510726050499729359425225648640123261740038466477199558622385392681431116708504786717792954423652175238523148502864261257958052160388320515554698676763961843558167584044194593826146489829114838011680847899646441557869464961871529399919853115738744234789160671547809952861567946113871225181625028907576844980525853226720960598107411629890602375027855220812391389358471936648501349470156090670336840371170794797749522085109173116945742370974193651637461434848087668715713047701058178715601224181241606396613932556708610053394386027421061365308207798425755541438495446844219406034480582981899294550662566012637369108414345868284606510374110284729891607923959313716563209266733192352089822273558777730978476511354153527305403341847023144603396358823073605093845982901631629688126673560978638251673360628002628731918632851476743093197164595597775001852371677818902258665981210453656799833411036114468571570486387664885284989578767923698566471852880066709144428366589950162611651055961638137566180897028663132721494303196958132655335210212623206937484602740891341175019021252964930532570590565375950031690095471573722914015878610314974463479273560906602926907943424254711923267915404309416044809360238509338596738385920300710951577048558401932259713025382319175137832450848127397914651251969286010188536372073349320325486142358795930963081224097272762217335738201364795257305198836133610389474949237841383265622372220156208683519897240551773193828329053293429226687164828194869451869296663999114630914681093650561576768145686863714237424654450779878298279833928787333275543404533415308640393628420459077189714666200897096998471922392836801962798773815810528413256490101679653170893021844670849213804546196239579095132671530066741629072031228581070681051386867700694389294844033161180214496021245729436935062931643756734167820627911066024041498278806296875165821385767611859893771178292148135870340417702674739244425535576553967044411345102060733865903403165406778610528373234517032651195487766486209493584931171382598048571919693096835195572108614825604605720997138155270149297810168560051535204623912941831394692755233552533188090313636563871332510720232812261538035129374311724273301088400625761029372357436292649064476515359459175886716072428020935131297847900852957722647447802700730203675467940009442302195248489475673221016139505931127814691365290887983976022168083644308739633760690104456179208504787702954826919136490133304886602371534816107049798995649973356004951949289787507485635824699081119489536646608641782143295393112205383602307090921128712504667850993829175792005561412915936038159125108426900977233053549558949345445501955157532151498132635040127172525827172380665232110228726455073231193030753197754754418533206605495220493208581951240335560363823709322021286157917878841460845108410566133516316944670028021391397980775529833662285417292616524995396024808883470662282764209596066225511076655123983727464318352216898547725591969331505185747017377612619332703578157261352187485054799441062632464494314437872002791300877821444116230412833571469083831637610890546061927546785913323374018241647967427133176613276345086933615124667251824955289753237390312309604480050161009955914276160930644461115683798293376911153805843989892654802837235711496287203876184283337142943928584338826300879500082682070426228456505271665994942474914680165867159700081278762596484483727305286919759956324385610581528737933720711125445921605597412213988205518283031827151649750003497264120581733438919142300577272083837845386851558391372100834993567920072886481180651044490617820434591030550474907625696955952092128211533647551400215161998152242011155195906610971015946431358729064504914171993841580613049024246440930796624646697292656742640428490221370739060588947356796173745600940370009775133419264102494055143613318106710016
```

### Install
1. Download `Encodid` from Github as a `.zip` file. Extract all files to a desired directory.
  (OPTIONAL) : Create a desktop shortcut to the files(`Encodid.exe` and `Encodid_Rewrite.exe`) by right clicking on the file and selecting "Create Shortcut." Drag this to your desktop.
2. Run `Encodid_Rewrite.exe`(or your desktop shortcut) to rewrite the key in `key.txt`. The key is set to "0" and must be changed. A new and unique sequence will always be given.
3. Run `Encodid.exe`(or your desktop shortcut) to encode or decode text. `Encodid` automatically decodes a sequence if it can, otherwise it will encode it, allowing you, the user, to type anything into the intake, and expect the correct outtake.

**IMPORTANT NOTE:** Antivirus applications may detect the script as a virus or malware. If you wish to use the application, add an exception to your antivirus applications for `Encodid.exe` and `Encodid_Rewrite.exe`.

### Keys
To share a key, simply upload the text file for others to download.

To create a new key, simply create `key.txt` if it does not already exist, and run `Encodid_Rewrite.exe`. It is noted that `key.txt` must remain in the same directory as `Encodid_Rewrite.exe`.

If you have someone else's key you want to use as your own, delete or store `key.txt` somewhere other than it's current directory. Add in the new key and rename it and it's extension `key.txt`.

### Uninstall
Simply delete the `Encodid` file and all relating files. If you added shortcuts, you may delete these.
