<h1 align="center">
  <br />
  <img
    src="./_docs/assets/icon.png"
    alt="API de Robôs do Mega Man"
    width="150"
  />
  <br />
  <b>API de Robôs do Mega Man</b>
  <br />
  <sub
    ><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml"
  
  </a>
  <a href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/felipeAguiarCode/MegaApiDotnetCore"
      alt="Última Versão"
    />
  </a>
</h1>

<p align="center">
  Esta é uma API (serviço online) que fornece informações sobre os chefes robóticos da série Mega Man. 
  Ela foi criada para desenvolvedores que desejam acessar dados como nomes, habilidades e detalhes dos robôs em formato JSON.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" alt="Exemplo de código" />
</p>

## Como Funciona? 🛠️

- **Para desenvolvedores**: Você pode fazer solicitações HTTP (como buscar ou adicionar dados) usando os endpoints abaixo.
- **Dados organizados**: A API usa tecnologias modernas para garantir que as informações sejam rápidas e confiáveis.

## Endpoints Principais 🌐

<table align="center">
  <tr>
    <th>Método</th>
    <th>Endpoint</th>
    <th>O que faz?</th>
  </tr>
  <tr>
    <td>GET</td>
    <td><code>/api/v1/robots</code></td>
    <td>Lista todos os robôs disponíveis</td>
  </tr>
  <tr>
    <td>GET</td>
    <td><code>/api/v1/robots/{id}</code></td>
    <td>Mostra detalhes de um robô específico (substitua <code>{id}</code> pelo número do robô)</td>
  </tr>
  <tr>
    <td>POST</td>
    <td><code>/api/v1/robots</code></td>
    <td>Adiciona um novo robô à lista (requer configuração técnica)</td>
  </tr>
</table>

## Tecnologias Usadas 💻

- **Entity Framework Core**: Gerencia os dados como um "organizador" de banco de dados.
- **RESTful API**: Padrão para criar serviços web de forma clara e eficiente.
- **Injeção de Dependência**: Técnica para tornar o código mais flexível e fácil de testar.

## Bibliotecas Importantes 📚

<table align="center">
  <tr>
    <th>Biblioteca</th>
    <th>Versão</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td><a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a></td>
  </tr>
</table>

## Licença 📜
Este projeto é open source e está sob a licença [MIT](https://opensource.org/licenses/MIT), que permite uso livre desde que os créditos sejam mantidos.

---

⌨️ Desenvolvido por **Felipe Aguiar** - 
[GitHub](https://github.com/felipeAguiarCode)
