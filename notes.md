# Change Notes
The following have been introduced to fix small design flaws.
- Removed `Bottom Padding` (`pb-70`) on `Choose Us` Section
- Removed `Bottom Padding` (`pb-70`) on `Explore Our Courses` Section
- Add `Top Padding` (`pt-100`) on `Carousel` Section (`class="centering-container"` -> `class="centering-container pt-100"`)


# Current Problems To Solve
- `Our Services` Section ->
	- Fix `text color` (#808080) and `text padding` (either 20px or same as `Why Choose Us` section)
	- Fix links on inner sections (Unable to click)

- `Carousel` Section -> temporary solution for **1920x1080 Screens** (Untested on mobile!)
	- `<style>` code section change `width` calculation under `.dslider .dslide-track`:
```
...
.dslider .dslide-track{
        animation:scroll 20s linear infinite;
        display:flex;
        width: 70000px;
    }
...
```


- `Explore Our Courses` Section ->
	- Fix `owl-nav` alignment (Align with section header)
	- Reverse animation (`solid` > `transparent` like in all other sections)


- `Our Trainers` Section ->
	- Fix `owl-nav` alignment (Align with section header)