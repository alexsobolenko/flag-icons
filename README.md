# flag-icons

## Description

A collection of all country flags in SVG — plus the CSS for easier integration.

For using the flags inline with text add the classes `.flag-icon` and
`.flag-icon-xxx` (where `xxx` is the
[ISO 3166-1-alpha-3 code](https://www.iso.org/obp/ui/#search/code/)
of a country) to an empty `<span>`. If you want to have a squared version flag
then add the class `flag-icon-squared` as well. Example:

```html
<span class="flag-icon flag-icon-sun"></span>
<span class="flag-icon flag-icon-sun flag-icon-squared"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`flag-icon-background` instead of `flag-icon` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 4 by 3 ratio or if it's squared
add also the `flag-icon-squared` class.

Many thanks to [lipis](https://github.com/lipis) for his repository, from which almost all the content was taken. Some flags have been added or changed. 
The alpha-2 code for alpha-3 has been replaced, and for some regions have been added alpha-3 like codes.
The project is compiled using SASS.

## List of flags

* 'abw' - Aruba
* 'afg' - Afghanistan
* 'ago' - Angola
* 'aia' - Anguilla
* 'ala' - Åland Islands
* 'alb' - Albania
* 'and' - Andorra
* 'are' - United Arab Emirates
* 'arg' - Argentina
* 'arm' - Armenia
* 'asm' - American Samoa
* 'ata' - Antarctica
* 'atf' - French Southern Territories
* 'atg' - Antigua and Barbuda
* 'aus' - Australia
* 'aut' - Austria
* 'aze' - Azerbaijan
* 'bdi' - Burundi
* 'bel' - Belgium
* 'ben' - Benin
* 'bes' - Bonaire, Sint Eustatius and Saba
* 'bfa' - Burkina Faso
* 'bgd' - Bangladesh
* 'bgr' - Bulgaria
* 'bhr' - Bahrain
* 'bhs' - Bahamas
* 'bih' - Bosnia and Herzegovina
* 'blm' - Saint Barthélemy
* 'blr' - Belarus
* 'blz' - Belize
* 'bmu' - Bermuda
* 'bol' - Bolivia (Plurinational State of Bolivia)
* 'bra' - Brasil
* 'brb' - Barbados
* 'brn' - Brunei Darussalam
* 'btn' - Bhutan
* 'bvt' - Bouvet Island
* 'bwa' - Botswana
* 'caf' - Central African Republic
* 'can' - Canada
* 'cat' - Catalonia (autonomous community in Spain)
* 'cck' - Cocos (Keeling) Islands
* 'che' - Switzerland
* 'chl' - Chile
* 'chn' - China (People's Republic of China)
* 'civ' - Côte d'Ivoire
* 'cmr' - Cameroon
* 'cod' - Congo (Democratic Republic of the Congo)
* 'cog' - Congo (Congo-Brazzaville)
* 'cok' - Cook Islands
* 'col' - Colombia
* 'com' - Comoros
* 'cpv' - Cabo Verde
* 'cri' - Costa Rica
* 'cub' - Cuba
* 'cuw' - Curaçao
* 'cxr' - Christmas Island
* 'cym' - Cayman Islands
* 'cyp' - Cyprus
* 'cze' - Czech Republic
* 'deu' - Germany (Federal Republic of Germany)
* 'dji' - Djibouti
* 'dma' - Dominica
* 'dnk' - Denmark
* 'dom' - Dominican Republic
* 'dza' - Algeria
* 'ecu' - Ecuador
* 'egy' - Egypt
* 'eng' - England (country that is part of the United Kingdom)
* 'eri' - Eritrea
* 'esh' - Western Sahara
* 'esp' - Spain
* 'est' - Estonia
* 'eth' - Ethiopia
* 'eun' - European Union (EU)
* 'fin' - Finland
* 'fji' - Fiji
* 'flk' - Falkland Islands (Malvinas)
* 'fra' - France
* 'fro' - Faroe Islands
* 'fsm' - Micronesia (Federated States of Micronesia)
* 'gab' - Gabon
* 'gbr' - United Kingdom of Great Britain and Northern Ireland
* 'geo' - Georgia
* 'ggy' - Guernsey
* 'gha' - Ghana
* 'gib' - Gibraltar
* 'gin' - Guinea
* 'glp' - Guadeloupe
* 'gmb' - Gambia
* 'gnb' - Guinea-Bissau
* 'gnq' - Equatorial Guinea
* 'grc' - Greece
* 'grd' - Grenada
* 'grl' - Greenland
* 'gtm' - Guatemala
* 'guf' - French Guiana
* 'gum' - Guam
* 'guy' - Guyana
* 'hkg' - Hong Kong (Special Administrative Region of the China)
* 'hmd' - Heard Island and McDonald Islands
* 'hnd' - Honduras
* 'hrv' - Croatia
* 'hti' - Haiti
* 'hun' - Hungary
* 'idn' - Indonesia
* 'imn' - Isle of Man
* 'ind' - India
* 'iot' - British Indian Ocean Territory
* 'irl' - Ireland
* 'irn' - Iran (Islamic Republic of Iran)
* 'irq' - Iraq
* 'isl' - Iceland
* 'isr' - Israel
* 'ita' - Italy
* 'jam' - Jamaica
* 'jey' - Jersey
* 'jor' - Jordan
* 'jpn' - Japan
* 'kaz' - Kazakstan
* 'ken' - Kenya
* 'kgz' - Kyrgyzstan
* 'khm' - Cambodia
* 'kir' - Kiribati
* 'kna' - Saint Kitts and Nevis
* 'kor' - Korea (Republic of Korea)
* 'kos' - Kosovo (partially recognised state of Serbia)
* 'kwt' - Kuwait
* 'lao' - Lao People's Democratic Republic
* 'lbn' - Lebanon
* 'lbr' - Liberia
* 'lby' - Libya
* 'lca' - Saint Lucia
* 'lie' - Liechtenstein
* 'lka' - Sri Lanka
* 'lso' - Lesotho
* 'ltu' - Lithuania
* 'lux' - Luxembourg
* 'lva' - Latvia
* 'mac' - Macau (Macao Special Administrative Region of China)
* 'maf' - Saint Martin (French part)
* 'mar' - Marokko
* 'mco' - Monaco
* 'mda' - Moldova (Republic of Moldova)
* 'mdg' - Madagascar
* 'mdv' - Maldives
* 'mex' - Mexico
* 'mhl' - Marshall Islands
* 'mkd' - Makedonia
* 'mli' - Mali
* 'mlt' - Malta
* 'mmr' - Myanmar
* 'mne' - Montenegro
* 'mng' - Mongolia
* 'mnp' - Northern Mariana Islands
* 'moz' - Mozambique
* 'mrt' - auritania
* 'msr' - Montserrat
* 'mtq' - Martinique
* 'mus' - Mauritius
* 'mwi' - Malawi
* 'mys' - Malaysia
* 'myt' - Mayotte
* 'nam' - Namibia
* 'ncl' - New Caledonia
* 'ner' - Niger
* 'nfk' - Norfolk Island
* 'nga' - Nigeria
* 'nic' - Nicaragua
* 'nir' - Northern Ireland (country that is part of the United Kingdom)
* 'niu' - Niue
* 'nld' - Netherlands (Holland)
* 'nor' - Norway
* 'npl' - Nepal
* 'nru' - Nauru
* 'nzl' - New Zealand
* 'omn' - Oman
* 'pak' - Pakistan
* 'pan' - Panama
* 'pcn' - Pitcairn
* 'per' - Peru
* 'phl' - Philippines
* 'plw' - Palau
* 'png' - Papua New Guinea
* 'pol' - Poland
* 'pri' - Puerto Rico
* 'prk' - Korea (Democratic People's Republic of Korea)
* 'prt' - Portugal
* 'pry' - Paraguay
* 'pse' - State of Palestine
* 'pyf' - French Polynesia
* 'qat' - Qatar
* 'reu' - Réunion
* 'rou' - Roumania
* 'rus' - Russia (russian Federation)
* 'rwa' - Rwanda
* 'sau' - Saudi Arabia
* 'sco' - Scotland (country that is part of the United Kingdom)
* 'sdn' - Sudan
* 'sen' - Senegal
* 'sgp' - Singapore
* 'sgs' - South Georgia and the South Sandwich Islands
* 'shn' - Saint Helena, Ascension and Tristan da Cunha
* 'sjm' - Svalbard and Jan Mayen  
* 'slb' - Solomon Islands
* 'sle' - Sierra Leone
* 'slv' - El Salvador
* 'smr' - San Marino
* 'som' - Somalia
* 'spm' - Saint Pierre and Miquelon
* 'srb' - Serbia
* 'ssd' - South Sudan
* 'stp' - Sao Tome and Principe
* 'sun' - Union of Soviet Socialist Republics (USSR)
* 'sur' - Suriname
* 'svk' - Slovakia
* 'svn' - Slovenia
* 'swe' - Sweden
* 'swz' - Swaziland
* 'sxm' - Sint Maarten (Dutch part)
* 'syc' - Seychelles
* 'syr' - Syrian Arab Republic
* 'tca' - Turks and Caicos Islands
* 'tcd' - Chad
* 'tgo' - Togo
* 'tha' - Thailand
* 'tjk' - Tajikistan
* 'tkl' - Tokelau
* 'tkm' - Turkmenistan
* 'tls' - Timor-Leste
* 'ton' - Tonga
* 'tto' - Trinidad and Tobago
* 'tun' - Tunisia
* 'tur' - Turkey
* 'tuv' - Tuvalu
* 'twn' - Taiwan, Province of China
* 'tza' - United Republic of Tanzania
* 'uga' - Uganda
* 'ukr' - Ukraine
* 'umi' - United States Minor Outlying Islands
* 'ury' - Uruguay
* 'usa' - United States of America (USA)
* 'uzb' - Uzbekistan
* 'vat' - Vanuatu
* 'vct' - Vatican
* 'ven' - Venezuela (Bolivarian Republic of Venezuela)
* 'vgb' - Virgin Islands (British)
* 'vir' - Virgin Islands (U.S.)
* 'vnm' - Vietnam
* 'vut' - Vanuatu
* 'wal' - Wales (country that is part of the United Kingdom)
* 'wlf' - Wallis and Futuna
* 'wsm' - Samoa
* 'yem' - Yemen
* 'zaf' - South Africa
* 'zmb' - Zambia
* 'zwe' - Zimbabwe
