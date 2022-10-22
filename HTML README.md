<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
</head>
<body>
    <div>
         <H1>Cadastro de DEVs</H1>
         <p>Complete suas informações</p>
         <br>
    </div>

    <form>
        <fieldset>
            <div>
                <label>Nome</label>
                <input type="text" name="nome" id="nome"
            </div>

            <div>
                <label>Sobrenome</label>
                <input type="text" name="sobrenome" id="sobrenome"
            </div>

        </fieldset>
        <div>
            <label>Email</label>
            <input type="email" name="email" id="email"
        </div>
        <div>
            <label>De qual lado da aplicação você desenvolve?</label>
            <label>
                <input type="radio" name="devweb" value="frontend" checked>Front-end
            </label>
            <label>
                <input type="radio" name="devweb" value="backend">Back-end
            </label>
            <label>
                <input type="radio" name="devweb" value="fullstack">Fullstack
            </label>
        </div>
        <div>
            <label>Senioridade</label>
            <select id="senioridade">
                <option selected disabled value="">Selecione</option>
                <option>Junior</option>
                <option>Pleno</option>
                <option>Senior</option>
            </select>
        </div>
        <fieldset>
            <div>
                <label> Selecione as tecnologias que utiliza.</label><br><br>
                <input type="checkbox" id="tecnologia" name="tecnologia1" value="HTML">
                <label for="tecnologia1"></label>HTML</label>
                <input type="checkbox" id="tecnologia" name="tecnologia2" value="CSS">
                <label for="tecnologia1"></label>CSS</label>
                <input type="checkbox" id="tecnologia" name="tecnologia3" value="Javascript">
                <label for="tecnologia1"></label>Javascript</label>
                <input type="checkbox" id="tecnologia" name="tecnologia4" value="PHP">
                <label for="tecnologia1"></label>PHP</label>
                <input type="checkbox" id="tecnologia" name="tecnologia5" value="C++">
                <label for="tecnologia1"></label>C++</label>
                <input type="checkbox" id="tecnologia" name="tecnologia6" value="Python">
                <label for="tecnologia1"></label>Python</label>
                <input type="checkbox" id="tecnologia" name="tecnologia7" value="Java">
                <label for="tecnologia1"></label>Java</label>
            </div>
        </fieldset>

    </form>




</body>
</html>
