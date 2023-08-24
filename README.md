# React coding challenge to hire a Front-end Software Engineer (Next.js and React)

## Introduction

This is a coding challenge to hire a Front-end Software Engineer (Next.js and React) for [AgSteward project](https://agsteward.com.au/).

## The challenge

The challenge is to build a simple web application that displays a list of farms and their details. The application should be built using [Next.js](https://nextjs.org/) and [React](https://reactjs.org/).

### Requirements

- The application should be built using Next.js and React.
- The application should be responsive.

### Bonus points
- The application should be deployed to [Vercel](https://vercel.com/).
- The application should be built using [Tailwind CSS](https://tailwindcss.com/).
- The application should be built using [TypeScript](https://www.typescriptlang.org/).

### Data

```
[
  {
    "id": 1,
    "name": "Farm 1",
    "address": "Address 1",
    "phone": "Phone 1",
    "email": "Email 1",
    "website": "Website 1",
    "latitude": -33.8688,
    "longitude": 151.2093,
    "managementAreasGeoJSON": "[{\"type\":\"Feature\",\"properties\":{\"projID\":\"1182\",\"P_Area\":\"Planting Area 1\",\"Area_ha\":1.79558500700593},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[147.51464523757747,-41.82394941055073],[147.51423754172447,-41.8239174301686],[147.51434482974423,-41.821390926972946],[147.5153962558114,-41.820831244974734],[147.51464523757747,-41.82394941055073]]]}},{\"type\":\"Feature\",\"properties\":{\"projID\":\"1182\",\"P_Area\":\"Planting Area 2\",\"Area_ha\":0.753104444593191},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[147.54822947542587,-41.81763059468868],[147.54889466331122,-41.817030900041516],[147.54978515684732,-41.816799016555315],[147.55032159875014,-41.81677502852547],[147.550740023383,-41.81638322342603],[147.55156614394895,-41.81654314408549],[147.5498548943313,-41.817062883818956],[147.54822947542587,-41.81763059468868]]]}},{\"type\":\"Feature\",\"properties\":{\"projID\":\"1182\",\"P_Area\":\"Planting Area 3\",\"Area_ha\":1.926778692612052},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[147.54434266059357,-41.81627365071558],[147.5447074411399,-41.8165934922846],[147.53707923712966,-41.816177698498386],[147.5373796445633,-41.81592182366327],[147.54434266059357,-41.81627365071558]]]}},{\"type\":\"Feature\",\"properties\":{\"projID\":\"1182\",\"P_Area\":\"Planting Area 4\",\"Area_ha\":1.185119518771768},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[147.54178919629763,-41.81053222257542],[147.54213251914442,-41.810700154639],[147.54105963543427,-41.8114998253045],[147.5404373628747,-41.81185167724724],[147.53970780192373,-41.81220352726519],[147.53823795115923,-41.81268331966691],[147.53813066274313,-41.812419434363306],[147.5396434288516,-41.81192364677676],[147.54082360096962,-41.8112999086138],[147.54178919629763,-41.81053222257542]]]}},{\"type\":\"Feature\",\"properties\":{\"projID\":\"1182\",\"P_Area\":\"Planting Area 5\",\"Area_ha\":3.100076848495007},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[147.5532690533663,-41.81206758439248],[147.5523249161763,-41.81604976001625],[147.5504151829832,-41.816081744510754],[147.55069413272406,-41.81576190033505],[147.55170264351085,-41.815697931233224],[147.55180993185513,-41.81547403914307],[147.5519172200932,-41.8144345299323],[147.55200305072827,-41.813906772642795],[147.5521317966732,-41.81315511081338],[147.5523249157134,-41.81277128008346],[147.55288281518412,-41.81198761852338],[147.5532690533663,-41.81206758439248]]]}}]"
  },
  {
    "id": 2,
    "name": "Farm 2",
    "address": "Address 2",
    "phone": "Phone 2",
    "email": "Email 2",
    "website": "Website 2",
    "latitude": -33.8688,
    "longitude": 151.2093,
    "managementAreasGeoJSON": "[{\"type\":\"Feature\",\"properties\":{\"projID\":\"1393\",\"Area_name\":\"Area 1\",\"Area_ha\":70.3},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[137.9564295730382,-33.509366567167596],[137.9572565731866,-33.50977756713278],[137.95879357344015,-33.51014056707061],[137.95637157324018,-33.513166567145426],[137.95419557306036,-33.51588356721257],[137.9539795730947,-33.51709456721323],[137.95366757312573,-33.5185085672163],[137.9523815729475,-33.51881756726437],[137.9506755727512,-33.51995156732344],[137.94828757247882,-33.521582567405765],[137.9491975726531,-33.522232567366274],[137.94881557266422,-33.523480567373106],[137.94911257279247,-33.524979567351856],[137.94886157275616,-33.52501256736151],[137.9468815723997,-33.52400956744484],[137.94620557234032,-33.52479156746619],[137.94550357226984,-33.52544456748925],[137.94537457224803,-33.525404567494576],[137.94579257226692,-33.52459956748346],[137.9460455722647,-33.523865567478246],[137.94601057223235,-33.52337856748283],[137.94528157209143,-33.52283456751465],[137.94640657219617,-33.521639567478644],[137.9465195721971,-33.52134656747606],[137.94569357205754,-33.52109256750987],[137.94634457210304,-33.5201295674907],[137.9469755722083,-33.52029856746506],[137.9477545722712,-33.51929856744121],[137.94656657204914,-33.51854756749228],[137.94796957217338,-33.516943567448045],[137.94924957228957,-33.515532567407256],[137.94968757239806,-33.51628956738538],[137.949735572455,-33.51718456737777],[137.95025757256383,-33.51771756735407],[137.95079557267607,-33.518267567329566],[137.9512385727215,-33.51787356731489],[137.95155457274595,-33.517448567305344],[137.9521815727688,-33.51614256728932],[137.95243557274438,-33.515006567286726],[137.9524075726169,-33.51278356730213],[137.95244557254554,-33.511392567309585],[137.95207457241403,-33.51003756733273],[137.95200157233296,-33.508774567343686],[137.95182757229173,-33.50850756735219],[137.95170957219128,-33.50701856736636],[137.9519195721909,-33.506436567361895],[137.95245557227577,-33.5064995673407],[137.95296557238888,-33.50714256731667],[137.95474657271566,-33.5081585672409],[137.9564295730382,-33.509366567167596]]]}}]"
  },
  {
    "id": 3,
    "name": "Farm 3",
    "address": "Address 3",
    "phone": "Phone 3",
    "email": "Email 3",
    "website": "Website 3",
    "latitude": -33.8688,
    "longitude": 151.2093,
    "managementAreasGeoJSON": "[{\"type\":\"Feature\",\"properties\":{\"projID\":\"1127\",\"P_Area\":\"Planting Area 1\",\"Area_ha\":8.54024836642449},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[143.792837,-36.665848],[143.796566,-36.666713],[143.796266,-36.668641],[143.796262,-36.668672],[143.792422,-36.668225],[143.792294,-36.668225],[143.792837,-36.665848]]]}}]"
  },
  {
    "id": 4,
    "name": "Farm 4",
    "address": "Address 4",
    "phone": "Phone 4",
    "email": "Email 4",
    "website": "Website 4",
    "latitude": -33.8688,
    "longitude": 151.2093,
    "managementAreasGeoJSON": "[{\"type\":\"Feature\",\"properties\":{\"projID\":\"1203\",\"P_Area\":\"Planting Area 1\",\"Area_ha\":7.227508},\"geometry\":{\"type\":\"Polygon\",\"coordinates\":[[[143.882124,-35.989848],[143.882103,-35.995473],[143.878949,-35.995456],[143.879035,-35.995091],[143.879721,-35.994865],[143.880386,-35.994153],[143.880665,-35.99365],[143.881159,-35.993268],[143.881631,-35.992782],[143.881803,-35.992452],[143.881674,-35.99207],[143.881438,-35.991792],[143.881202,-35.991497],[143.881159,-35.991081],[143.881094,-35.990751],[143.881223,-35.990334],[143.880966,-35.989987],[143.880944,-35.989744],[143.882124,-35.989848]]]}}]"
  },
  {
    "id": 5,
    "name": "Farm 5",
    "address": "Address 5",
    "phone": "Phone 5",
    "email": "Email 5",
    "website": "Website 5",
    "latitude": -33.8688,
    "longitude": 151.2093,
    "managementAreasGeoJSON": "[{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 3\",\"type\":\"Remnant management\",\"area_ha\":2.015},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.1084003567911,-41.01009318947829],[147.10940043266282,-41.01075945780448],[147.10944837703505,-41.01101840135283],[147.10942215601486,-41.01121101181766],[147.10714215644438,-41.01128801164203],[147.10722315657097,-41.01023101164226],[147.1084003567911,-41.01009318947829]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 4\",\"type\":\"Remnant management\",\"area_ha\":3.197},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.10686365248324,-41.00946596418132],[147.1070479142358,-41.008591473710986],[147.10711015681647,-41.00856801162395],[147.107496156766,-41.00839001165283],[147.10687224977391,-41.00786496653724],[147.1068617543897,-41.00783363231508],[147.10692430094852,-41.00719082824198],[147.10710787268397,-41.00714009905469],[147.10722766290198,-41.00687744732982],[147.1080985345896,-41.00694667203986],[147.10829102655018,-41.007942707690475],[147.10800394796908,-41.008011521410566],[147.10846738704734,-41.00837690885678],[147.10861215643308,-41.00926401174394],[147.10706715667237,-41.00970101162722],[147.10686365248324,-41.00946596418132]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 5\",\"type\":\"Remnant management\",\"area_ha\":13.121},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.08289942382382,-41.01031762075435],[147.08292602779932,-41.010315689606344],[147.08346678816224,-41.00946996449154],[147.08346740143176,-41.009469287878815],[147.0834677421946,-41.00946929362623],[147.0834919779851,-41.0094697023922],[147.0847095208846,-41.00954851587781],[147.08500490133892,-41.00926692021801],[147.0850301609829,-41.00926400992455],[147.08567416093268,-41.008713009971004],[147.0865751607435,-41.00882701004121],[147.0868111606066,-41.00950701006329],[147.0862531606338,-41.01010601002367],[147.08628521421687,-41.01132480184608],[147.0862536562791,-41.01133995372539],[147.0859550107067,-41.01154390290325],[147.08603304017223,-41.01209811536589],[147.08591780474475,-41.012205271648426],[147.07981616163002,-41.01193600953793],[147.0800741617695,-41.0105270095497],[147.08044995948424,-41.010496227319194],[147.08058950392078,-41.01065478965496],[147.08114390547178,-41.010703486746436],[147.08170906410066,-41.010470420475265],[147.0826720121081,-41.010480884427004],[147.0828991733587,-41.01031780056891],[147.08289942382382,-41.01031762075435]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 5\",\"type\":\"Remnant management\",\"area_ha\":3.789},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.08844094177195,-41.011635066467264],[147.08822475266706,-41.011881966305616],[147.08877144078224,-41.01191459889595],[147.089660180225,-41.01171406723217],[147.09147503763003,-41.01163215219809],[147.09227944863503,-41.01175378396458],[147.09264815917612,-41.01177024728712],[147.09264815907775,-41.01250201053063],[147.0861325064564,-41.01221474210848],[147.08623422147758,-41.01188181208576],[147.08655481702894,-41.011797329652346],[147.08686571313254,-41.01178080111913],[147.08692045355005,-41.01171017541512],[147.08844094177195,-41.011635066467264]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 2\",\"type\":\"Remnant management\",\"area_ha\":26.656},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.1120031555419,-41.011025102171885],[147.11217732943615,-41.010717026437845],[147.11200315560998,-41.01051921962559],[147.11200315567547,-41.01003260334913],[147.11411636747735,-41.01004911384143],[147.11460209777886,-41.01052318637475],[147.11505326463202,-41.01055630659811],[147.11555919631726,-41.010994154376846],[147.11547915432374,-41.015093012307645],[147.10775415560525,-41.016647011720025],[147.108097155783,-41.014834011736134],[147.10841920015798,-41.01459104403648],[147.11138532811594,-41.01314635296561],[147.11114676135,-41.01269099811135],[147.11104744568237,-41.01260809677644],[147.11200315542592,-41.01188701202084],[147.1120031555419,-41.011025102171885]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 4\",\"type\":\"Remnant management\",\"area_ha\":8.114},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.10821058824223,-41.00680329465421],[147.10663129084537,-41.00669229507582],[147.10661715718174,-41.006560011574386],[147.10732515716714,-41.00565301162384],[147.10792615719933,-41.00455201166394],[147.10367715799066,-41.00476201133712],[147.10402015802902,-41.00398501135916],[147.10492215784632,-41.00405001142916],[147.10773315730623,-41.00403401164603],[147.10790415741042,-41.003014011653434],[147.10869815724638,-41.0030950117152],[147.10878854986174,-41.00363274620171],[147.10858876727988,-41.00378308592467],[147.10881900626896,-41.00446548050972],[147.10948783995963,-41.004417395090556],[147.109986156815,-41.00445501182238],[147.1101791566929,-41.00508601184092],[147.10820515684716,-41.00677001169827],[147.10821058824223,-41.00680329465421]]]]}},{\"type\":\"Feature\",\"properties\":{\"Region\":\"NNRM\",\"projID\":\"1372\",\"name\":\"Management Area 1\",\"type\":\"Remnant management\",\"area_ha\":73.019},\"geometry\":{\"type\":\"MultiPolygon\",\"coordinates\":[[[[147.09521343875377,-41.01856898446653],[147.09627611849365,-41.01443045052489],[147.0951076420825,-41.01375707339321],[147.09501105688793,-41.00936382485559],[147.09503000294123,-41.00936538388526],[147.0987811265069,-41.00972640612808],[147.0985707641318,-41.01002267989518],[147.09951747229206,-41.010101611575706],[147.09968416268842,-41.009868093470224],[147.10346550341077,-41.01021779972206],[147.10386874416835,-41.01035601238148],[147.10480674936085,-41.01037706306769],[147.10501021494002,-41.01064701543571],[147.1050215846888,-41.01253951986772],[147.10455064980766,-41.01403841335789],[147.1048879285679,-41.01458510112442],[147.10476106231022,-41.01508309402093],[147.10499919976235,-41.01525354342516],[147.10467910792576,-41.015526592440224],[147.10475460964506,-41.01574580782094],[147.10494887692985,-41.015836557625995],[147.10497801885325,-41.015959543924176],[147.1050421905657,-41.01596925050518],[147.10505015603985,-41.017295011515095],[147.09522315770556,-41.01901101076661],[147.09521343875377,-41.01856898446653]]]]}}]"    
  }
]
```

### Design

You can suggest any design that fits this simple application. You can use the following design as a reference.

![Design](./design.png)

### Submission

You can submit your solution by sending a link to your repository.

### Questions

If you have any questions, please send an email to [info@lapisit.com.au](mailto:info@lapisit.com.au).
