---
# Course title, summary, and position.
linktitle: 
summary: Learn how to use Academic's docs layout for publishing online courses, software documentation, and tutorials.
weight: 1

# Page metadata.
title: თბილისი, როგორც ურბანული თანაკვეთის სივრცე
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

## Flexibility

<p align="justify">
გმირთა მოედანმა ბოლო რამდენიმე წელიწადში მნიშნველოვანი ტრანსფორმაცია განიცადა. 2011 წელს  აშენდა ორდონიანი ესტაკადა, რომლის ერთ ნაწილიც დაუკავშირდა მდინარე ვერეს ხეობაში ასევე ახალაშენებულ მაგისტრალს. <a href="https://idfi.ge/ge/news-66"> 115 მლნ ლარად </a> შეფასებული ინფრასტრუქტურის შექმნის მთავარ მიზანს ქალაქის საცობებისგან განტვირთვა წარმოადგენდა (ყოველ შემთხვევაში, ეს იყო საჯაროდ გაცხადებული მიზანი). 
2015 წლის ივნისში ეს ადგილი ქალაქის ბოლო ასწლეულის ისტორიაში მომხდარი ერთ-ერთი ყველაზე დიდი წყალდიდობის ეპიცენტრი იყო, რომელმაც რამდენიმე ათეული ადამიანის სიცოცხლე და თბილისის ზოოპარკის ბინადრები იმსხვერპლა. თბილისის მერიამ ამ სტიქიის შემდეგ, მაინც გადაწყვიტა კატასტროფის ზონაში, წყალდიდობის შედეგად დანგრეული ინფრასტრუქტურის აღდგენა, რომელსაც დამატებით  <a href="http://tbilisi.gov.ge/news/1358"> 15 მლნ ლარამდე</a> დასჭირდა.
არასწორი სატრანსპორტო პოლიტიკის და მიღებული გადაწყვეტილებების უწყვეტი ჯაჭვით,  ამ მოედანზე არსებული საცობები არათუ გაქრა, არამედ ვითარება კიდევ უფრო გაუარესდა, რადგან ახალმა ინფრასტრუქტურამ ავტომობილების უფრო მეტი ნაკადი მიიზიდა. ბიუჯეტიდან უსარგებლოდ დახარჯულ მილიონებს კი მოგვიანებით, ადამიანური ტრაგედიაც დაემატა. 
თუმცა წყალდიდობისა და ვერეს ხეობის <a href="http://www.wmo.int/pages/prog/hwrp/RA6/documents/2016/session3/Flash-Flood-events-Georgia2015-Megrelidze.pdf"> დატბორვის ზონად </a> მიჩნევის მიუხედავად, საგზაო ინფრასტრუქტურის გარშემო შექმნილი სივრცე დღესაც მიმზიდველია კერძო დეველოპერებისთვის, რომლებიც უძრავი ქონებით სპეკულაციით და ქალაქის ადმინისტრაციის <a href="https://netgazeti.ge/news/339122/"> ხელშეწყობით </a> განაგრძობენ <b>მოგების მაქსიმიზაციას!</b></p>

## Delete tutorials

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
