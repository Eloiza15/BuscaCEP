🏠 Sistema de Busca de CEP - Windows Forms C#
📋 Descrição
Este é um sistema desenvolvido com Windows Forms em C# que realiza a busca de informações de um endereço a partir do CEP informado pelo usuário. A aplicação utiliza uma API RESTful para obter os dados e exibi-los em uma interface gráfica amigável.

⚙️ Tecnologias Utilizadas
Linguagem: C#

Plataforma: .NET (Windows Forms)

API: ViaCEP (ou similar para busca de CEP)

Biblioteca de terceiros: Newtonsoft.Json (para manipulação de JSON)

🧱 Estrutura do Projeto
Endereco.cs: Classe responsável por armazenar os dados retornados da API (logradouro, bairro, localidade, UF).

ServerCep.cs: Classe que realiza a requisição HTTP para a API, trata o JSON e retorna um objeto do tipo Endereco.

BuscaCEP.cs: Interface principal onde o usuário digita o CEP e visualiza os dados. Também contém funções para:

Minimizar

Fechar

Mover a janela com clique e arraste do mouse

📦 Instalação de Pacotes
Antes de rodar o projeto, instale o pacote Newtonsoft.Json via NuGet:

bash
Copiar
Editar
Install-Package Newtonsoft.Json
🖥️ Funcionalidades
✅ Busca de endereço pelo CEP

✅ Exibição de logradouro, bairro, cidade e UF

✅ Interface limpa e estilizada

✅ Janela personalizável (sem bordas)

✅ Minimizar e fechar com botões personalizados

✅ Movimentação da janela via PanelSuperior

▶️ Como Executar
Clone o projeto ou abra o .sln no Visual Studio.

Instale os pacotes NuGet necessários.

Compile e execute.

Digite um CEP e clique em Buscar.

📷 Tela do Sistema
Janela centralizada e sem borda

Painel superior com título e botões de controle

Área central com imagem, campos de texto e botão de busca
