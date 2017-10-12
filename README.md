<title>HTML LAB Form</title>
<style>
  body
  {
    background-color:tomato;
     text-align:left;
     
  }

 h1
 {
   text-align:center;
   text-
 }
  
   
</style>

<body>
<h1>FORM</h1>

<form>
  
  <label>First name</label>
  <input type="text" />
  <br>
  
  <label>Last name</label>
  <input type="text" />
  <br>
  <label>DOB</label>
  <input type="DATE" required/>
  <br>
  <label>Gender</label>
  <input type="radio" value="M" name="RG"/>MALE
  <input type="radio" value="F" name="RG"/>FEMALE
  <br>
  <label>Course</label>
  <select name="class">
    <option value="Select">Select</option>
    <option value="B.Sc">B.Sc</option>
    <option value="B.Sc">M.Sc</option>
    <option value="B.Sc">B.Tech</option>
    <option value="B.Sc">B.Pharm</optio>
    <option value="B.Sc">M.Tech</option>
    <option value="B.Sc">M.Pharm</option>
  </select>
  
  <br>
  <label>Adress</label>
  <textarea name="adress"></textarea>
  <br>
  <label>Subjects</label>
 <input type="checkbox" value="ckmath" />Mathematics
 <input type="checkbox" value="ckphy" />Physics
  <input type="checkbox" value="ckchem" />Chemistry
  <input type="checkbox" value="ckbio" />Biology
  <br>
  <label>Upload Image</label>
  <input type="file" />
  <br>
  
  <input type="submit" />
  <input type="reset" />
    
</form>
</body>
