---
title: Zephyr: Recreating the Demo - Help Center
description: Your Guide to Recreating Elements of the Zephyr Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/zephyr:Zephyr

---

Help Center
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Help Center`      |  
| Show Title | Show               |  
| Position   | bottom-c           |  
| Status     | Published          |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<ul class="bullet-1">
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=164">Frequently Asked Questions</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=164">Written Documentation</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=164">Video Guides &amp; Aids</a></li>
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=164">Member Support Forum</a></li>
</ul>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting      |  
| :------------------ | :----------- |  
| Module Class Suffix |              |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
[demo5]: assets/demo_1d.jpeg
