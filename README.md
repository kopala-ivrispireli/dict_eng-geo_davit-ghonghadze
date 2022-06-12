# dict_eng-geo_davit-ghonghadze

*************************************************************
**                                                         **
** ინგლისურ-ქართული ელექტრონული ლექსიკონი Goldendict-თვის. **
**                                                         **
** ავტორი: დავით ღონღაძე.                                  **
**                                                         **
*************************************************************

The insturction in Englis see below.

ფაილი dict_eng-geo_a-z_davit-ghonghadze.xdxf წარმოადგენს ლექსიკონს, პროგრამისთვის goldendict.

იმისთვის, რომ გამოიყენოთ ლექსიკონი სისტემაში უნდა გქონდეთ დაყენებული პროგრამა goldendict.
goldendict-ის თქვენი სისტემისთვის შესაბამისი ვერსია შეგიძლიათ ნახოთ და ჩამოტვირთოთ მისამართიდან:
http://goldendict.org/download.php

Linux-ის დისტრიბუტივებში, უმეტეს შემთხვევაში, შესაძლებელია რეპოზიტორებიდან:

Debian/Ubuntu:
1.
    sudo apt update
    ან
    sudo apt-get update
2.
    sudo apt install goldendict
    ან
    sudo apt-get install goldendict


Fedora:
1.
    sudo yum makecache --refresh
2.
    sudo yum -y install goldendict
    

ამჟამად ფაილში განმარტებულია/დამუშავებულია 110 ელემენტი (სიტყვა, ასო, არტიკლი, კავშირი, სიტყვათ შეთანხმება, ფრაზა და ა.შ.).
ლექსიკონში სიტყვების დამატება გრძელდება.

როგორ დავამატოთ ეს ლექსიკონი პროგარმას goldendict

1)ჩამოტვითეთ რეპოზიტორიდან ფოლდერი/საქაღალდე მასში მოთავსებული ლექსიკონით და სხვა ფაილებით.
    რეპოზიტორი:
    https://github.com/kopala-ivrispireli/dict_eng-geo_davit-ghonghadze.git
    
        ა) გადადით ლინკზე: https://github.com/kopala-ivrispireli/dict_eng-geo_davit-ghonghadze.git
        ბ) მონახეთ მწვანე ღილაკი წარწერით "Code". ღილაკზე სიტყვა "Code"-ის მარხნივ იქნება პატარა სამკუთხედი ქვემოთ მიმართული წვერით.
        გ) დააჭირეთ მწვენე ღილაკს წარწერით "Code"
        დ) ჩამოიშლება ფუნქციური დამხმარე ფანჯარა და ჩამონათვალში დაწყკაპეთ წარწერა: Download ZIP
        ე) ჩამოტვირთული ZIP-არქივი შეინახეთ თქვენთვის სასურველ ადგილას და ამოაარქივეთ.

2) გახსენით პროგრამა goldendict

    >>> მე-2, მე-3, მე-4 ნაბიჯის მაგივრად, goldendict-ის გახსნის შემდეგ, დააჭირეთ F3 -ს <<<

3) ინსტრუმენტების მთავარ დაფაზე იპოვეთ ჩანართი Edit

4) დაწკაპეთ თაგვის (მაუსის) მარცხენა ღილაკით Edit-ზე

5) ჩამოშლილ ფუნქციურ სარკმელში თაგვის (მაუსის) მარცხენა ღილაკით დაწკაპეთ Dictionaries



6) გაიხსნება ახალი ფანჯარა Dictionaries

7) ფანჯარაში ავტომატურად გახსნილია ჩვენთვის საჭირო ჩანართები:
    ჩანართი Sources
    და Sources ჩანართში ქვეჩანართი: Files
    
    თუ ფანჯარა სხვა ჩანართებს შემოგთავაზებთ გადადით Sources-ში და აქ კი Files-ში.
    
8) მარჯვენა კიდეზე დავინახავთ:
    ზემოთ: Add... და Remove
    ქვემოთ: Rescan now
    
   მარჯვენა ქვემო კუთხეში სამი ღილაკია
   OK
   Apply
   Cancel
   
9) დავაჭიროთ ღილაკს Add...

10) გაიხსნება საფაილო სისტემაში სანავიგაციო ფანჯარა, ანუ ფაილებისა და ფოლდერების დასათვალიერებელი ფანჯარა

11) ვიპოვოთ სად გვაქვს შენახული ფოლდერი dict_eng-geo_davit-ghonghadze

12) მოვნიშნოთ ფოლდერი dict_eng-geo_davit-ghonghadze და სანავიგაციო ფანჯრის მარჯვენა ქვედა კუთხეში დავაჭიროთ ღილაკს OK

13) სანავიგაციო ფანჯარა დაიხურება და დავინახავთ რომ ფანჯარაში Dictionaries, შუა ველზე დაემატება სტრიქონი ჩვენს მიერ დამატებული ფოლდერის სრული მისამართით.
    ვთქვათ თუ ფოლდერი dict_eng-geo_davit-ghonghadze შენახული გვაქვს დირექტორიაში /home/USERNAME/Documents/
    მაშინ დამატებული სტრიქონი იქნება ასეთი:
    /home/USERNAME/Documents/dict_eng-geo_davit-ghonghadze

14) ამის შემდეგ დავაჭიროთ ღილაკებს შემდეგი თანმიმდევრობით:
    
    Rescan now
    
    Apply
    
    OK
    
15) OK-ზე დაჭერის შემდეგ ფანჯარა Dictionaries დაიხურება და თქვენ შეგიძლიათ გამოიყენოთ ლექსიკონი.

16) თარგმნილია დაახლოებით 110 ელემენტი, ამიტომ შესამოწმებლად შეგიძლიათ ნახოთ სიტყვები:
    
    good
    better
    best
    assert
    assertion
    assertive
    
    
    
----------------------------------------
    
ნელნელა ვაგრძელებ სიტყვების დამატებას.

----------------------------------------




*************************************************************
**                                                         **
** Englis-Georgian digital dictionary for Goldendict       **
**                                                         **
** Author: Davit Ghonghadze                                **
**                                                         **
*************************************************************

The file dict_eng-geo_a-z_davit-ghonghadze is a dictionary for the program GoldenDict

To use the dictionary you have to install program GoldenDict
Installation files for your system you can find on address:
http://goldendict.org/download.php

Now-day I can translate just 110 elements (words, phrases, articles etc.)
I continue to work for the dictionary.

How to add the dictionary to the program GoldenDict

1. Download the dictionary from the repository and save it into directory you wish;
    Repository:
    https://github.com/kopala-ivrispireli/dict_eng-geo_davit-ghonghadze.git

2. Open the program GoldenDict

3. Click on F3 (or Edit --> Dictionaries)

4. In opened window click the button Add...

5. In opened navigation window find directory where you have saved the downloaded folder (dict_eng-geo_davit-ghonghadze) with the dictionary

6. Click on the folder dict_eng-geo_davit-ghonghadze and then click on the button OK

7. The navigation window will close

8. In the window Dictionaries click buttons:

    Rescan now
    
    Apply
    
    OK
    
9. The dictionary is ready to use.

10. As I mentioned above I translated just 110 elements.
    So if you want to check how the dictionary works try to find words:
    
    good
    better
    best
    assert
    assertion
    assertive
    ...
