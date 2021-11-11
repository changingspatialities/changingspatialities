---
# Course title, summary, and position.
linktitle: 
summary: ისტორიული სივრცითი მონაცემების გაციფრულების მიზნით
weight: 1

# Page metadata.
title: QGIS-ის გამოყენება
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: მიმოხილვა
    weight: 1
---

## შესავალი

QGIS ან Quantum GIS წარმოადგენს საყოველთაო გამოყენების, ღია, უფასო გეოსაინფორმაციო სისტემას და არის სივრცითი ანალიზისა და მოდელირების ერთ-ერთი ყველაზე გავრცელებული პროგრამა მსოფლიოში. თავისი არსით, იგი წარმოადგენს კომერციული პროგრამის ArcGIS ალტერნატივას, რამეთუ ძირითადად იქმნება და ვითარდება ღია სამეცნიერო და მოხალისეობრივ საწყისებზე. უფრო მეტი QGIS-ის შესახებ შეგიძლიათ იხილოთ პროექტის <a href="https://qgis.org/en/site/"> მთავარ გვერდზე</a>. 

სურვილის შემთხვევაში, დამწყები მომხმარებლებისთვის არსებობს <a href="https://docs.qgis.org/3.22/en/docs/user_manual/">ზოგადი გზამკვლევი,</a> <a href="https://docs.qgis.org/3.22/en/docs/training_manual/index.html">ტრენინგის სახელმძღვანელო</a> და <a href="https://qgis.org/en/site/forusers/trainingmaterial/index.html">ტუტორიალები</a>.

საჭიროებიდან გამომდინარე, ჩვენ `ტრენინგის სახელმძღვანელოს` მხოლოდ ერთ ნაწილს დავეყრდნობთ და ვკონცენტრირებდით ვექტორული ინფორმაციის შექმნაზე, შენახვასა და ვიზუალიზაციაზე.

## ინსტალაცია

QGIS მუშაობს Windows, macOS, Linux და Android პლატფორმებზე. სასურველია, ამ კონკრეტული დავალებისთვის გადმოვწეროთ და დავაყენოთ ნებისმიერი ვერსია QGIS 3.16.0 ან ზემოთ. უახლესი, QGIS 3.22 ვერსიის დაყენებისგან უმჯობესია თავი შევიკავოთ, რადგან ახალი რელიზია და შესაძლებელია ჯერ კიდევ არ იყოს სრულყოფილად სანდო. 

საინსტალაციო ფაილები:  
\* Windows სისტემისთვის იხილეთ <a href="https://qgis.org/downloads/">აქ</a> 
macOS სისტემისთვის იხილეთ <a href="https://www.kyngchaos.com/software/archive/qgis/">აქ</a>

\* შენიშვნა  
Windows სისტემისთვის განკუთვნილ გვერდზე გადასვლისას არ დაგაბნიოთ საინსტალაციო ფაილის სახელწოდებამ. სასურველი ფაილის სახელი `QGIS-OSGeo4W` ამ ფორმით გვხვდება, რომელსაც მოსდევს ვერსიის ნომერი, მაგალითად `3.16.7-1` და ბოლოვდება `.exe` ან `msi` გაფართოებით.

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
