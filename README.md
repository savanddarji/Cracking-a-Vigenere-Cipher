# Cracking-a-Vigenere-Cipher
Comments and reviews will be appreciated: If you need any help please don't hesitate to contact me on : darji@uwindsor.ca or                                                                                                                     savanddarji@gmail.com

Recover the encryption key and plain text of the vigenere cipher text using Kerckhoff's method.

 The project is about the implementation of Kerchoff's method to crack vigenere cipher using python 2.7.12.
 The code results number of coincedences with corresponding shifts in descending order.

The sample result is shown as below:

    Number of coincidences for 1 shift is: 67
    Number of coincidences for 2 shift is: 77
    Number of coincidences for 3 shift is: 75
    Number of coincidences for 4 shift is: 73
    Number of coincidences for 5 shift is: 151
    Number of coincidences for 6 shift is: 70
    Number of coincidences for 7 shift is: 85
    Number of coincidences for 8 shift is: 80
    Number of coincidences for 9 shift is: 65
    Number of coincidences for 10 shift is: 113
    Number of coincidences for 11 shift is: 76
    Number of coincidences for 12 shift is: 77
    Number of coincidences for 13 shift is: 77
    Number of coincidences for 14 shift is: 81
    Number of coincidences for 15 shift is: 152
    Number of coincidences for 16 shift is: 69
    Number of coincidences for 17 shift is: 69
    Number of coincidences for 18 shift is: 81
    Number of coincidences for 19 shift is: 79
    Number of coincidences for 20 shift is: 113
    Maximum number of coincidence(L): 152
    Second highest number of coincidence(L1): 151
    Third highest number of coincidence:(L2) 113
    Fourth highest number of coincidence:(L3) 85
    Fifth highest number of coincidence(L4): 81
    Sixth highest number of coincidence:(L5) 80

    Possible key lengths are: 15 , 5 , 10 , 7 , 14 , 8
    gcf of all above shifts: 1

    Take 15 as key length
    The Encryption Key: CHAOSCHAOSCHAOS

    Your plain Text for the key CHAOSCHAOSCHAOS is:
    eoftheestateaswepassedthroughoneofthegatesonourwayhomeagainaprettyyoungwomanofgipsytypecomingintheoppositedirectionbowedandsmiled
    thatsaprettygirliremarkedappreciativelyjohnsfacehardenedthatismrsraikestheonethatmisshowardexactlysaidjohnwithratherunnecessary
    abruptnessithoughtofthewhitehairedoldladyinthebighouseandthatvividwickedlittlefacethathadjustsmiledintooursandavaguechillofforebodin
    gcreptovermeibrusheditasidestylesisreallyagloriousoldplaceisaidtojohnhenoddedrathergloomilyyesitsafinepropertyitllbeminesomedayshoul
    dbeminenowbyrightsifmyfatherhadonlymadeadecentwillandthenishouldntbesodamnedhardupasiamnowhardupareyoumydearhastingsidontmindtelling
    youthatimatmywitsendformoneycouldntyourbrotherhelpyoulawrencehesgonethrougheverypennyheeverhadpublishingrottenversesinfancybindings
    nowereanimpecuniouslotmymothersalwaysbeenawfullygoodtousimustsaythatisuptonowsincehermarriageofcoursehebrokeofffrowningforthefirst
    timeifeltthatwithevelynhowardsomethingindefinablehadgonefromtheatmosphereherpresencehadspeltsecuritynowthatsecuritywasremovedand
    theairseemedrifewithsuspicionthesinisterfaceofdrbauersteinrecurredtomeunpleasantlyavaguesuspicionofeveryoneandeverythingfilledmymind
    justforamomentihadapremonitionofapproachingevilchapteriithethandthofjulyihadarrivedatstylesonthethofjulyicomenowtotheeventsofthet
    handthofthatmonthfortheconvenienceofthereaderiwillrecapitulatetheincidentsofthosedaysinasexactamanneraspossibletheywereelicited
    subsequentlyatthetrialbyaprocessoflongandtediouscrossexaminationsireceivedaletterfromevelynhowardacoupleofdaysafterherdeparture
    tellingmeshewasworkingasanurseatthebighospitalinmiddlinghamamanufacturingtownsomefifteenmilesawayandbeggingmetoletherknowifmrsingle
    thorpshouldshowanywishtobereconciledtheonlyflyintheointmentofmypeacefuldayswasmrscavendishsextraordinaryandformypartunaccountable
    preferenceforthesocietyofdrbauersteinwhatshesawinthemanicannotimaginebutshewasalwaysaskinghimuptothehouseandoftenwentoffforlong
    expeditionswithhimimustconfessthatiwasquiteunabletoseehis

    Take 5 as key length
    The Encryption Key: CHAOS

    Your plain Text for the key CHAOS is:
    eoftheestateaswepassedthroughoneofthegatesonourwayhomeagainaprettyyoungwomanofgipsytypecomingintheoppositedirectionbowedandsmiled
    thatsaprettygirliremarkedappreciativelyjohnsfacehardenedthatismrsraikestheonethatmisshowardexactlysaidjohnwithratherunnecessary
    abruptnessithoughtofthewhitehairedoldladyinthebighouseandthatvividwickedlittlefacethathadjustsmiledintooursandavaguechillofforebodin
    gcreptovermeibrusheditasidestylesisreallyagloriousoldplaceisaidtojohnhenoddedrathergloomilyyesitsafinepropertyitllbeminesomedayshoul
    dbeminenowbyrightsifmyfatherhadonlymadeadecentwillandthenishouldntbesodamnedhardupasiamnowhardupareyoumydearhastingsidontmindtelling
    youthatimatmywitsendformoneycouldntyourbrotherhelpyoulawrencehesgonethrougheverypennyheeverhadpublishingrottenversesinfancybindings
    nowereanimpecuniouslotmymothersalwaysbeenawfullygoodtousimustsaythatisuptonowsincehermarriageofcoursehebrokeofffrowningforthefirst
    timeifeltthatwithevelynhowardsomethingindefinablehadgonefromtheatmosphereherpresencehadspeltsecuritynowthatsecuritywasremovedand
    theairseemedrifewithsuspicionthesinisterfaceofdrbauersteinrecurredtomeunpleasantlyavaguesuspicionofeveryoneandeverythingfilledmymind
    justforamomentihadapremonitionofapproachingevilchapteriithethandthofjulyihadarrivedatstylesonthethofjulyicomenowtotheeventsofthet
    handthofthatmonthfortheconvenienceofthereaderiwillrecapitulatetheincidentsofthosedaysinasexactamanneraspossibletheywereelicited
    subsequentlyatthetrialbyaprocessoflongandtediouscrossexaminationsireceivedaletterfromevelynhowardacoupleofdaysafterherdeparture
    tellingmeshewasworkingasanurseatthebighospitalinmiddlinghamamanufacturingtownsomefifteenmilesawayandbeggingmetoletherknowifmrsingle
    thorpshouldshowanywishtobereconciledtheonlyflyintheointmentofmypeacefuldayswasmrscavendishsextraordinaryandformypartunaccountable
    preferenceforthesocietyofdrbauersteinwhatshesawinthemanicannotimaginebutshewasalwaysaskinghimuptothehouseandoftenwentoffforlong
    expeditionswithhimimustconfessthatiwasquiteunabletoseehis


    Take 10 as key length
    The Encryption Key: CHAOSCHAOS

    Your plain Text for the key CHAOSCHAOS is:
    eoftheestateaswepassedthroughoneofthegatesonourwayhomeagainaprettyyoungwomanofgipsytypecomingintheoppositedirectionbowedandsmiled
    thatsaprettygirliremarkedappreciativelyjohnsfacehardenedthatismrsraikestheonethatmisshowardexactlysaidjohnwithratherunnecessary
    abruptnessithoughtofthewhitehairedoldladyinthebighouseandthatvividwickedlittlefacethathadjustsmiledintooursandavaguechillofforebodin
    gcreptovermeibrusheditasidestylesisreallyagloriousoldplaceisaidtojohnhenoddedrathergloomilyyesitsafinepropertyitllbeminesomedayshoul
    dbeminenowbyrightsifmyfatherhadonlymadeadecentwillandthenishouldntbesodamnedhardupasiamnowhardupareyoumydearhastingsidontmindtelling
    youthatimatmywitsendformoneycouldntyourbrotherhelpyoulawrencehesgonethrougheverypennyheeverhadpublishingrottenversesinfancybindings
    nowereanimpecuniouslotmymothersalwaysbeenawfullygoodtousimustsaythatisuptonowsincehermarriageofcoursehebrokeofffrowningforthefirst
    timeifeltthatwithevelynhowardsomethingindefinablehadgonefromtheatmosphereherpresencehadspeltsecuritynowthatsecuritywasremovedand
    theairseemedrifewithsuspicionthesinisterfaceofdrbauersteinrecurredtomeunpleasantlyavaguesuspicionofeveryoneandeverythingfilledmymind
    justforamomentihadapremonitionofapproachingevilchapteriithethandthofjulyihadarrivedatstylesonthethofjulyicomenowtotheeventsofthet
    handthofthatmonthfortheconvenienceofthereaderiwillrecapitulatetheincidentsofthosedaysinasexactamanneraspossibletheywereelicited
    subsequentlyatthetrialbyaprocessoflongandtediouscrossexaminationsireceivedaletterfromevelynhowardacoupleofdaysafterherdeparture
    tellingmeshewasworkingasanurseatthebighospitalinmiddlinghamamanufacturingtownsomefifteenmilesawayandbeggingmetoletherknowifmrsingle
    thorpshouldshowanywishtobereconciledtheonlyflyintheointmentofmypeacefuldayswasmrscavendishsextraordinaryandformypartunaccountable
    preferenceforthesocietyofdrbauersteinwhatshesawinthemanicannotimaginebutshewasalwaysaskinghimuptothehouseandoftenwentoffforlong
    expeditionswithhimimustconfessthatiwasquiteunabletoseehis
