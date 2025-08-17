# APP

Gympass style app.

## RFs

- [x] Deve ser possível se cadastrar;
- [x] Deve ser possível se autenticar;
- [x] Deve ser possível obter um perfil de usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter o seu número de histório de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [x] Deve ser possível o usuário realizar check-in em uma academia;
- [x] Deve ser possível validar o check-in de um usuário;



## RNs

- [x] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [x] O usuário não pdoe fazer 2 check-ins no mesmo dia;
- [x] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado por administadores;
- [ ] A academia só pode ser cadastrada por administradores;
- [ ] O check-in só pode ser validado em até 20 minutos após criados;


## RNFs

- [x] A senha do usuário precisa ser criptografada;
- [x] Os Ddaos da aplicação precisam estar persistidos no PostgresSQL;
- [ ] Todas as listas de dados devem estar paginadas com até 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT;