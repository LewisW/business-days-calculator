business-days-calculator
========================

Business Days Calculator


[![Build Status](https://travis-ci.org/andrejsstepanovs/business-days-calculator.png?branch=master)](https://travis-ci.org/andrejsstepanovs/business-days-calculator) [![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/andrejsstepanovs/business-days-calculator/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/andrejsstepanovs/business-days-calculator/)[![Coverage Status](https://coveralls.io/repos/andrejsstepanovs/business-days-calculator/badge.png?branch=master)](https://coveralls.io/r/andrejsstepanovs/business-days-calculator?branch=master) [![Latest Stable Version](https://poser.pugx.org/andrejsstepanovs/business-days-calculator/v/stable.png)](https://packagist.org/packages/andrejsstepanovs/business-days-calculator) [![License](https://poser.pugx.org/andrejsstepanovs/business-days-calculator/license.png)](https://packagist.org/packages/andrejsstepanovs/business-days-calculator)


# Examples

    $calc = new BusinessDays();
    $date = new \DateTime('2000-01-01');

    $calc->setStartDate($date);
    $calc->addBusinessDays(2);
    var_dump($calc->getDate());
