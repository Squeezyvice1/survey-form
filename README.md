<!DOCTYPE html>
<html lang="en">
  <header>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css" />
    <title>nice ways of making money</title>
  </header>
  <body>
    <h1 id="title">lets make money together</h1>
    <p id="description" class="established">lets all share with one another all the way each of us can make money </p>
    <form id="survey-form" action='https://survey-form.freecodecamp.rocks/?name=Jan&email=jan.mlinaric%40gmail.com&age=22&role=student&user-recommend=definitely&mostLike=challenges&prefer=back-end-projects&comment=a'>
      <fieldset>
        <label id="name-label">Name</label>
          <input id="name" type="text" placeholder="Enter your name" required >
        <label id="email-label">Email</label>
          <input id="email" type="email" placeholder="Enter your Email" required >
        <label id="number-label">phone number</label> <input id="number" type="number" min="10" max="99" placeholder="phone number">
        <label for="how you make money"> In which ways are you currently making money</label>
          <select id="dropdown">
            <option value="">Select current options</option>
            <option value="1">forex</option>
            <option value="2">full time work 9 to 5</option>
            <option value="3">part time job</option>
            <option value="4">born privilaged</option>
            <option value="5">Other</option>
          </select>
      </fieldset>
      <fieldset>
        <label> Do you think coding as a good career path is still relevent in the year 2025?</label>
          <label for="Definitely">Definitely</label>
            <input type="radio" class="inline" name="attribute" value="1"> 
          <label for="Maybe">Maybe</label>
            <input type="radio" class="inline" name="attribute" value="2" >
          <label for="Not sure">Not sure</label>
            <input type="radio" class="inline" name="attribute" value="3" >
      </fieldset>
      <fieldset>
        <label> What do you think is the best way that will never fail you in making money ? </label>
          <select id="dropdown2">
            <option value="">Select an option</option>
            <option value="1">learning a hard skill like coding</option>
            <option value="2">trading</option>
            <option value="3">entrepreneur</option>
            <option value="4">content creation</option>
          </select>
       
      </fieldset>
      <fieldset>
        <label for="money making ways">chose all the options that you would try for youself personally to try and make money  </label>
        <label for="trading">Forex</label>
          <input type="checkbox" class="inline" value="forex"> 
        <label for="heavy course">Studying a heavy course</label>
          <input type="checkbox" class="inline" value="heavy course"> 
        <label for="entrepreneurship">Entrepreneurship</label>
          <input type="checkbox" class="inline" value="entrepreneurship" > 
        <label for="digital products">Selling digital products</label>
          <input type="checkbox" class="inline" value="digital products">
        <label for="iligal">Doing something iligal</label>
          <input type="checkbox" class="inline" value="iligal" >
        <label for="miracle">Praying for a miracle</label>
          <input type="checkbox" class="inline" value="Miracle">
        <label for="lottory">Winning the lottory</label>
        <input type="checkbox" class="inline" value="lottory" >
      </fieldset>
      <fieldset>
        <label for="suggestions"> Any comments or suggestions?</label>
          <textarea rows="5" cols="50" placeholder="Dont be shy speak up!..."></textarea>
        
      </fieldset>
      <fieldset>
        <input type="submit" value="Submit" id="submit" />
      </fieldset>
    </form>
  </body>
</html>
