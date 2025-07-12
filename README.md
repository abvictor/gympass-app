# APP

Gympass style app.

## RFs

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter um perfil de usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter o seu número de histório de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;



## RNs

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pdoe fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado por administadores;
- [ ] A academia só pode ser cadastrada por administradores;
- [ ] O check-in só pode ser validado em até 20 minutos após criados;


## RNFs

- [ ] A senha do usuário precisa ser criptografada;
- [ ] Os Ddaos da aplicação precisam estar persistidos no PostgresSQL;
- [ ] Todas kustas de dados devem estar paginadas com até 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT;