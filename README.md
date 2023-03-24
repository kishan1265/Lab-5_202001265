<h1 align="center"><b><center>IT314-Software Engineering Lab-5 </center></b></h1>
<h2 align="center"><b>Static Analysis </center></b></h2>

<h4 align="center"><b> Name : </b> Kishan Sangani</h4>
<h4 align="center"><b> Id : </b> 202001265</h4>

<h2>Cloning repo with link : </h2>
https://github.com/kishan1265/woc4.0-eventmanager-kishan.git

![1](https://user-images.githubusercontent.com/97011040/227481033-a96df4e8-c418-4c13-8351-0afa55895c30.png)

### Installing mypy but it is already installed :-
![2](https://user-images.githubusercontent.com/97011040/227481374-4f2c8695-8f83-4b4c-8d4d-49a67b28dc8c.png)


### Analyzing file: ./registration/views.py
## Error 1 :-
![3](https://user-images.githubusercontent.com/97011040/227481410-c95c84cd-7e01-4e09-b5f6-42b7bc1c8881.png)

### After correcting errors :-
![4](https://user-images.githubusercontent.com/97011040/227481478-75d1758c-bc0c-48ba-91a9-9719f65eb55b.png)


<b> Success: </b> no issues found in 1 source file

## Error 2 :-
![image](https://user-images.githubusercontent.com/97011040/227483259-73a0a271-22f7-4dd9-b73d-904e29477563.png)

error: expected an indented block after 'if' statement on line 15 <br>
Found 1 error in 1 file (errors prevented further checking)

## Error 3 :-
![6](https://user-images.githubusercontent.com/97011040/227484921-05b7db10-378a-47bc-bdc7-076a6e600c83.png)

error: expected ':' <br>
Found 1 error in 1 file (errors prevented further checking)

## Error 4 :-
![7](https://user-images.githubusercontent.com/97011040/227488197-33a04b12-20a6-4619-aec0-ce17d8d320fa.png)

error: cannot assign to attribute here. Maybe you meant '==' instead of '='? <br>
Found 1 error in 1 file (errors prevented further checking)

## Error 5 :-
![8](https://user-images.githubusercontent.com/97011040/227488770-729185ab-698b-4a1c-b6c6-5b9bb2c95487.png)

error: unterminated string literal (detected at line 57) <br>
Found 1 error in 1 file (errors prevented further checking)

### Analyzing file: ./registration/models.py
## Error 6 :-
![9](https://user-images.githubusercontent.com/97011040/227492302-cdc41bdd-dee3-4ed5-a05d-0f87dcf46849.png)

error: Name "Model" is not defined <br>
Found 4 errors in 1 file (checked 1 source file)

## Error 7 :-
![10](https://user-images.githubusercontent.com/97011040/227493432-fa92e9ef-8e8a-4f17-9e08-eff04e64096f.png)

error: invalid syntax. Perhaps you forgot a comma? <br>
Found 1 error in 1 file (errors prevented further checking)

