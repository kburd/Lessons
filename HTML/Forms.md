# HTML Forms

Author: Kaleb Burd

Length: 3 hours

---

## Text Input
```html
<form>
    <input type="text">
</form>
```

## Labels
```html
<form>
    <label for="fname">First Name:</label>
    <input type="text" id="fname">
</form>
```

## Sumbit
```html
<form>
    <label for="fname">First Name:</label>
    <input type="text" id="fname"><br>
    <input type="submit" value="Submit">
</form>
```

## Value Attribute
```html
<form>
    <label for="fname">First Name:</label>
    <input type="text" id="fname" value="firstName"><br>
    <input type="submit" value="Submit">
</form>
```

## Exercise 1: Last name field
```html
<form>
    <label for="lname">Last Name:</label>
    <input type="text" id="lname" value="lastName"><br>
    <input type="submit" value="Submit">
</form>
```

## Date Field
```html
<label for="birthday">Birthday:</label><br>
<input type="date" id="birthday" name="birthday">
```

## Radio Buttons
```html
<label>What is your favorite Album</label><br>
<input type="radio" name="favAlbum" value="mmlp"><label>The Marshall Mathers LP</label><br>
<input type="radio" name="favAlbum" value="eminemShow"><label>The Eminem Show</label><br>
<input type="radio" name="favAlbum" value="revival"><label>Revival</label><br>
```

## Exercise 2: Create a multiple choice question

>
> What is the largest planet?
> * Sun
> * Pluto
> * Moon
> * Jupiter
>

```html
<html>
    <label>What is the largest planet?</label><br>
    <input type="radio" name="largestPlanet" value="a"><label>Sun</label><br>
    <input type="radio" name="largestPlanet" value="b"><label>Pluto</label><br>
    <input type="radio" name="largestPlanet" value="c"><label>Moon</label><br>
    <input type="radio" name="largestPlanet" value="c"><label>Jupiter</label><br>
</html>
```

## Checkboxes
```html
<label>Which of the following songs do you like?</label><br>
<input type="checkbox" name="song1" value="withoutMe"><label>Without Me</label><br>
<input type="checkbox" name="song2" value="forgotAboutDre"><label>Forgot About Dre</label><br>
<input type="checkbox" name="song3" value="rapGod"><label>Rap God</label><br>
<input type="checkbox" name="song4" value="godzilla"><label>Godzilla</label><br>
<input type="checkbox" name="song5" value="stan"><label>Stan</label><br>
```

## Select/Option
```html
<label>What is your favorite artist to feature with Eminem?</label><br>
<select name="rating">
    <option value="1">Rihanna</option>
    <option value="2">Dr. Dre</option>
    <option value="3">Logic</option>
    <option value="4">Nate Dogg</option>
</select>
```

### Exercise 3: What day of the week is it?
```html
<label>What day of the week is it?</label><br>
<select name="dayOfWeek">
    <option value="Sunday">Sunday</option>
    <option value="Monday">Monday</option>
    <option value="Tuesday">Tuesday</option>
    <option value="Wednesday">Wednesday</option>
    <option value="Thursday">Thursday</option>
    <option value="Friday">Friday</option>
    <option value="Saturday">Saturday</option>
</select>
```

## Required
```html
<label for="fname">First Name:</label>
<input required type="text" id="fname">
```

## Disabled
```html
<label for="birthday">Birthday:</label><br>
<input disabled type="date" id="birthday" name="birthday">
```

## Validation
```html
<label for="lname">Last Name:</label>
<input pattern=".{3,}" type="text" id="lname" value="lastName"><br>
<input type="submit" value="Submit">
```
