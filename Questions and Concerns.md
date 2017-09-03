# prj-rev-bwfs-tea-cozy

As stated, there are many ways to deal with this project.  Since we had focused on flexbox recently, I took the opportunity to utilize it in many different locations. My concern is if using too many <div> tags will somehow affect performance of the site in the long term AND/OR if I am using Flexbox incorrectly by needing <div> to adjust simple tags.  I found I could not have control of things like <h2> tags unless they were within a <div> and I could not use <span><h2></h2></span>.  If you have a better idea, please let me know.

For CSS - I feel like I am not using the selectors in an ideal way. Logically, I feel like there would be a way to select children of a parent that I just selected. For instance, if you had a body and header section: that you could select the body:
body{
css
}

then select the child somehow like:

> header. 

I know there is things like body > header {} to target only the header in the body tag, but more looking for a shorthand of not even needing to write out body.  This becomes more clear when you deal with some like main .cat_section .first_row h2, main .cat_section .second_row h2, main .cat_section .third_row h2 {}.  It seems there would be a quicker way to get to the h2 tags of .first_row, .second_row, and third_row while still be specific with the target within main .cat_section.
I could be crazy but it just feels like the CSS could be improved, but I am not sure how.

I spent a solid 10 hours on this project nonstopped and then reviewed my work this morning. I would appreicate any feedback - good or bad. 

Thank you for your time,

Chase Norton
