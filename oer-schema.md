![schematized page](/assets/Screen Shot 2018-05-14 at 10.25.56 PM.png)

# Adding OER Schema

One of the primary reasons to use a tool that publishes in HTML format is to take advantage of metadata, the standards vehicle for OER Schema. Though we don't yet have the remix tools, we can prepare for this future now, by schematizing.

Let's take a look at some basics.

## Adding an Assessment

1. Highlight the name of your assignment: ![add assessment](/assets/Screen Shot 2018-05-14 at 9.08.38 PM.png)
2. Click the inline gizmo button on the floating toolbar: ![gizmo](/assets/Screen Shot 2018-05-14 at 9.08.48 PM.png)
3. Choose OER as the presentation method: ![Present as OER](/assets/Screen Shot 2018-05-14 at 9.08.55 PM.png)
4. Choose the `typeof` from the dropdown list as "**Assessment**." ![OER Gizmo fields](/assets/Screen Shot 2018-05-14 at 9.09.39 PM.png)
5. In the "Advanced" tab, copy the resource id at the bottom:
![resource id](/assets/Screen Shot 2018-05-14 at 10.10.12 PM.png)

## Adding a Learning Objective

Now, we can add a learning objective that points to this assessment. This is where schema can start to become interesting

1. Write the learning objectives: ![learning objectives](/assets/Screen Shot 2018-05-14 at 9.12.41 PM.png)
2. Add schema via the inline gizmo. ![gizmo](/assets/Screen Shot 2018-05-14 at 9.08.48 PM.png)
3. Choose OER as the presentation method: ![Present as OER](/assets/Screen Shot 2018-05-14 at 9.08.55 PM.png)
4. Now you can add the id from the assessment as a **related resource** and now the two are linked via OER Schema!: ![learning objective related resource](/assets/Screen Shot 2018-05-14 at 9.13.12 PM.png)

## Additional schema

Try adding the following if you have them on your page, and link them using the assessment resource id:

- **typeof:** _assessment_, **property:** _description_
- **typeof:** _supporting material_, **property:** _name_
- **typeof:** task, **property:** _name_
- **typeof:** topic, **property:** _name_