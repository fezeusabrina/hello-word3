#Je suis Sabrina

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="menu.css">
    <title>Document</title>
</head>
<body>
    <form action="">
        <fieldset>
            <legend>Formulaire</legend>
            <div class="milieu">
                <div class="left">
                    <div class="top"><label for="nom"> Nom:</label></div>
                    <div class="top"><label for="prenom">Prenom:</label></div>
                    <div class="top"><label for="email">Email:</label></div>
                    <div class="top"><label for="password">password:</label></div>
                    <div class="top"><label for="sexe">Sexe:</label></div>
                    <div class="top"><label for="file">Photo:</label></div>
                    <div class="top"><label for="">Contry:</label></div>
                    <div class="top"><label for="">prefered language:</label></div>
                </div>
                <div class="right">
                    <div class="top"><input type="text" placeholder="Enter Nom"></div>
                    <div class="top"><input type="text" placeholder="Enter prenom"></div>
                    <div class="top"><input type="email" placeholder="Enter email "></div>
                    <div class="top"><input type="password" placeholder="Enter password"></div>
                    <div class="top">
                       <label for="radio">Male</label> <input type="radio" name="radio">
                       <label for="radio">Feminine</label> <input type="radio" name="radio" >
                    </div>
                    <div class="top"><input type="file" ></div>
                    <div>
                        <select name="" id="">
                            <option value="">France</option>
                            <option value="">Cameroun</option>
                        </select>
                    </div>

                    <div>
                        <select name="pets" multiple size="4">
                            <optgroup>
                                <option value="css">css</option>
                                <option value="web">web</option>
                                <option value="java">java</option>
                                <option value="html">html</option>
                            </optgroup>
                            
                        </select>
                    </div>
                </div>
                    

            </div>

            <div>
                <input type="radio" name="radio" id="radio" />
                <label for="radio">L'esprit de la radio</label>
            </div>

            <div>
                <input type="se" name="radio" id="radio" />
                <label for="radio">faculte:</label>
            </div>

            

            <div>
                <input type="checkbox" >
                <label for="checkbox">foot</label>
            </div>

            <div>
                <button>Envoyer</button>
            </div>
                

        </fieldset>
    </form>
    
</body>
</html>
