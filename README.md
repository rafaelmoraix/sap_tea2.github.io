<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu com Submenus</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="views/stilo_home.css"> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    
</head>
<body>

    <div class="sidebar">
        <h2>Cadastros</h2>
        <ul>
            <li>
                <a href="#">
                    <i class="fas fa-user"></i> Pessoa
                    <ul class="submenu">
                        <li><a href="#" data-target="formulario-tipo-pessoa"><i class="fas fa-user-tag"></i> Tipo Pessoa</a></li>
                        <li><a href="#" data-target="formulario-vincula"><i class="fas fa-link"></i> Vincula</a></li>
                    </ul>
                    <div id="formulario-tipo-pessoa" class="formulario" style="display: none;">
                        <form>
                          <h2>Tipo Pessoa</h2>
                          <label for="nome">Nome:</label>
                          <input type="text" id="nome" name="nome" required>
                          
                          <label for="teste">teste:</label>
                          <input type="text" id="teste" name="" required>
                          
                      
                          <label for="descricao">Descrição:</label>
                          <textarea id="descricao" name="descricao"></textarea>
                      
                          <button type="submit">Salvar</button>
                        </form>
                      </div>
                    
                </a>
            </li>
            <li><a href="#"><i class="fas fa-users"></i> Usuários</a></li>
            <li><a href="#"><i class="fas fa-building"></i> Instituição</a></li>
            <li><a href="#"><i class="fas fa-landmark"></i> Orgão</a></li>
            <li><a href="#"><i class="fas fa-graduation-cap"></i> Modalidade de Ensino</a></li>
            <li><a href="#"><i class="fas fa-chalkboard-teacher"></i> Turma</a></li>
            <li>
                <a href="#">
                    <i class="fas fa-school"></i> Escola
                    <ul class="submenu">
                        <li><a href="#" data-target="formulario-cad-escola"><i class="fas fa-users-class"></i> Cadastro da Escola</a></li>
                        <li><a href="#" data-target="formulario-enturmar"><i class="fas fa-users-class"></i> Enturmar</a></li>
                        <li><a href="#" data-target="formulario-vincular-docentes"><i class="fas fa-user-plus"></i> Vincular Docentes</a></li>
                    </ul>
                    <div id="formulario-cad-escola" class="formulario" style="display: none;">
                        <form>
                          <h2>Cadastro da Escola</h2>
                          <div class="elemento">
                            <div>
                                <label>Nome da escola<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o nome da escola' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>CEP<br></br></label>
                                <input class="inputgeral" style="width: 100%;" id="cep" type='text' placeholder=' * *   * * * - * * * ' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Logradouro<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Rua, Alameda...' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Bairro<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Município<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Cidade' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Complemento<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Número<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Estado<br></br></label>
                                <select class="selectgeral" style="width: 100%;" autoComplete='off'>
                                    <option value=""></option>
                                    <option value="PE">PE</option>
                                    <option value="RO">RO</option>
                                    <option value="AC">AC</option>
                                    <option value="AM">AM</option>
                                    <option value="RR">RR</option>
                                    <option value="PA">PA</option>
                                    <option value="AP">AP</option>
                                    <option value="TO">TO</option>
                                    <option value="MA">MA</option>
                                    <option value="PI">PI</option>
                                    <option value="CE">CE</option>
                                    <option value="RN">RN</option>
                                    <option value="PB">PB</option>
                                    <option value="AL">AL</option>
                                    <option value="SE">SE</option>
                                    <option value="BA">BA</option>
                                    <option value="MG">MG</option>
                                    <option value="ES">ES</option>
                                    <option value="RJ">RJ</option>
                                    <option value="SP">SP</option>
                                    <option value="PR">PR</option>
                                    <option value="SC">SC</option>
                                    <option value="RS">RS</option>
                                    <option value="MS">MS</option>
                                    <option value="MT">MT</option>
                                    <option value="GO">GO</option>
                                    <option value="DF">DF</option>
                                </select>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Telefone da Escola<br></br></label>
                                <input class="inputgeral" style="width: 100%;" id="telefone-escola" type='text' placeholder='( * * ) * * * * * - * * * *' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Email da escola<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o email da escola' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Gestor<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Insira o gestor da escola' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Coordenador<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Insira o coordenador da escola' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>CNPJ<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' id="cnpj"  placeholder='__.____.____ / ______' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="di">
                            <button class="submitbtn" type='submit'>Salvar</button> <button class="cancelbtn">Cancelar</button>
                          </div>
                        </form>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <i class="fas fa-user-graduate"></i> Alunos
                    <ul class="submenu">
                        <li><a href="#" data-target="formulario-cad-aluno"><i class="fas fa-users-class"></i> Cadastro do Aluno</a></li>
                        <li><a href="#" data-target="formulario-matricula"><i class="fas fa-book-reader"></i> Matrícula</a></li>
                        <li><a href="#" data-target="formulario-transferir"><i class="fas fa-exchange-alt"></i> Transferir</a></li>
                    </ul>
                    <div id="formulario-cad-aluno" class="formulario" style="display: none;">
                        <form>
                          <h2>Cadastro de aluno</h2>
                          <div class="elemento">
                            <div>
                                <label>Nome da escola<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o nome da sua escola' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Nome do aluno<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o seu nome' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Data de Nascimento<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='date' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Nome do responsável<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o nome do seu responsável' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Email do responsável<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o email do seu responsável' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Telefone do responsável<br></br></label>
                                <input class="inputgeral" style="width: 100%;" id="telefone-resp" type='text' placeholder='( * * ) * * * * * - * * * *' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Registro do Aluno<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o seu RA' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>INEP da escola<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o código do Inep' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Ano Escolar<br></br></label>
                                <select class="selectgeral" style="width: 100%;" autoComplete='off'>
                                    <option value="">Selecione o ano</option>
                                </select>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Série<br></br></label>
                                <select class="selectgeral" style="width: 100%;" autoComplete='off'>
                                    <option value="">Selecione a série</option>
                                </select>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Turma<br></br></label>
                                <select class="selectgeral" style="width: 100%;" autoComplete='off'>
                                    <option value="">Selecione a turma</option>
                                </select>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Segmento<br></br></label>
                                <select class="selectgeral" style="width: 100%;" autoComplete='off'>
                                    <option value="">Selecione o segmento</option>
                                </select>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Nome do Professor Regular<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o nome do seu professor' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Nome do Professor Atendimento Educacional Especializado<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite o nome do professor atendente' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="elemento">
                            <div>
                                <label>Equipe Multidisciplinar<br></br></label>
                                <input class="inputgeral" style="width: 100%;" type='text' placeholder='Digite qual a equipe multidisciplinar' autoComplete='off'/>
                            </div>
                          </div>
                          <div class="di">
                            <button class="submitbtn" type='submit'>Salvar</button> <button class="cancelbtn">Cancelar</button>
                          </div>
                        </form>
                    </div>
                </a>
            </li>
        </ul>

        <h2>Inventários</h2>
        <ul>
            <li>
                <a href="#">
                    <i class="fas fa-clipboard-list"></i> Inventários
                    <ul class="submenu">
                        <li><a href="#" data-target="formulario-eixos"><i class="fas fa-chart-pie"></i> Eixos</a></li>
                        <li><a href="#" data-target="formulario-propostas"><i class="fas fa-lightbulb"></i> Propostas</a></li>
                    </ul>
                </a>
            </li>
        </ul>

        <h2>Relatórios</h2>
        <ul>
            <li><a href="#"><i class="fas fa-school"></i> Relatórios Geral </a></li>
        </ul>

        <h2>Migrações</h2>
        <ul>
            <li><a href="#"><i class="fas fa-school"></i> Escola</a></li>
            <li><a href="#"><i class="fas fa-user-graduate"></i> Aluno</a></li>
        </ul>
    </div>

    <div id="formulario-container" style="display: none;"></div> 

    <script>
        const menuItems = document.querySelectorAll('.sidebar li a');

        menuItems.forEach(item => {
            if (item.querySelector('.submenu')) {
                // ... (código para adicionar seta indicadora, se necessário) ...
            }

            if (item.dataset.target) {
                item.addEventListener('click', function(event) {
                    event.preventDefault(); 

                    const formularios = document.querySelectorAll('[id^="formulario-"]');
                    formularios.forEach(el => el.style.display = 'none');

                    const formularioId = this.dataset.target;
                    const formulario = document.getElementById(formularioId);
                    formulario.style.display = 'block'; 
                });
            }
        });

        document.querySelector('#telefone-resp').addEventListener('input', function(e) {
            let validtel = e.target.value.replace(/\D/g, "").substring(0, 11);
            console.log(validtel);
            let seqtel = validtel.split(""); 
            let telform = "";

            if (seqtel.length > 0) {
                telform += `(${seqtel.slice(0, 2).join("")}`;
            }
            if (seqtel.length > 2) {
                telform += `) ${seqtel.slice(2, 7).join("")}`;
            }
            if (seqtel.length > 6) {
                telform += ` - ${seqtel.slice(7, 11).join("")}`;
            }

            
            e.target.value = telform;
        });

        document.querySelector('#telefone-escola').addEventListener('input', function(e) {
            let validtel = e.target.value.replace(/\D/g, "").substring(0, 11);
            let seqtel = validtel.split("");
            let telform = "";
            
            if (seqtel.length > 0) {
                telform += `(${seqtel.slice(0, 2).join("")}`;
            }
            if (seqtel.length > 2) {
                telform += `) ${seqtel.slice(2, 7).join("")}`;
            }
            if (seqtel.length > 6) {
                telform += ` - ${seqtel.slice(7, 11).join("")}`;
            }
            
            e.target.value = telform;
        })

        document.querySelector('#cep').addEventListener('input', function(e) {
            let validcep = e.target.value.replace(/[^0-9,]/g, '').substring(0,8)
            let seqcep = validcep.split("")
            let cepform = ""
            
            if(seqcep.length > 0){
                cepform += `${seqcep.slice(0,2).join("")}`
            }
            if(seqcep.length > 2){
                cepform += ` ${seqcep.slice(2,5).join("")}`
            }
            if(seqcep.length > 5){
                cepform += ` - ${seqcep.slice(5,8).join("")}`
            }
            e.target.value = cepform
        })

        document.querySelector('#cnpj').addEventListener('input', function(e) {
            let validseq = e.target.value.replace(/[^0-9,]/g, '').substring(0,14)
            let seqcnpj = validseq.split("")
            let cnpjform = ""

            if (seqcnpj.length > 0){
                cnpjform += `${seqcnpj.slice(0,2).join("")}`
            }
            if (seqcnpj.length > 2)
            {
                cnpjform += `.${seqcnpj.slice(2,5).join("")}`
            }
            if (seqcnpj.length > 5)
            {
                cnpjform += `.${seqcnpj.slice(5,8).join("")}`
            }
            if (seqcnpj.length > 8)
            {
                cnpjform += `/${seqcnpj.slice(8,12).join("")}`
            }
            if (seqcnpj.length > 12)
            {
                cnpjform += ` - ${seqcnpj.slice(12,14).join("")}`
            }

            e.target.value = cnpjform
        })
    </script>
    

    <script src="views/home.js"></script> 
</body>
</html>
