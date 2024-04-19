# Phishing para Captura de Senhas do Facebook 🪪🎣

## Ferramentas Utilizadas 🔧

- Virtual Box
- Kali Linux
- SEToolkit

## Configurando o Phishing no Kali Linux ⚙️

### 1. Acesso Root

- Abra o terminal como root. Se estiver em um terminal regular, utilize o comando `sudo su` para acessar como root.

```console
$ sudo su
```

### 2. Instalação do SEToolkit

- Certifique-se de que o SEToolkit está instalado. Caso contrário, instale-o utilizando o seguinte comando:

```console
$ apt-get install setoolkit
```

### 3. Executando o SEToolkit

- Abra o terminal como root. Se estiver em um terminal regular, utilize o comando `sudo su` para acessar como root.

```console
$ sudo su
```
### 4. Configuração do Phishing

<details>
<summary>Após iniciar o SEToolkit você irá visualizar o menu principal:</summary>


![Tela do SEToolkit](/img/image-3.png)

- Digite o número 1 para selecionar a opção: "Social-Engineering Attacks".
</details>

<details>
<summary><code>Social-Engineering Attacks</code></summary>

![Social-Engineering Attacks](/img/image-4.png)

- Digite o número 2 para selecionar a opção: 
"Website Attack Vectors".
</details>

<details>
<summary><code>Website Attack Vectors</code></summary>

![Website Attack Vectors](/img/image-1.png)

- Digite o número 3 para selecionar a opção: "Credential Harvester Attack Method".
</details>

<details>
<summary><code>Credential Harvester Attack Method</code></summary>

![Credential Harvester](/img/image-2.png)

- Digite o número 2 para selecionar a opção: "Site Cloner".
</details>

<details>
<summary><code>Site Cloner</code></summary>

```console
> IP address for the POST back in Harvester/Tabnabbing [000.000.0.0]:
```

- Essa é a mensagem que aparecerá no console, onde no: `[000.000.0.0]` conterá o IP que você vai utilizar. Então é so pressionar Enter para confirmar.

```console
> Enter the url to clone:
```

- Aqui você digitará o site que deseja clonar, no nosso exemplo será o `http://www.facebook.com`

    Obs: Para esse nosso exemplo deverá ser utilizado exatamente essa url, com o `http` e não com o `htpps`. Então pressione Enter.

    ![Clonagem de site](/img/image-6.png)

 - Se essa mensagem apareceu significa que seu site cloner ja está rodando no IP que foi informado.
</details>


## Visualizando o Site Clonado 👁️

Devido à política de segurança (CORS), os navegadores atuais impedem que esse teste seja executado corretamente.

<details>
<summary>O que é CORS?</summary>

- A política CORS é aplicada para proteger os usuários da web contra ataques de segurança, como ataques de script entre sites (XSS) e roubo de informações confidenciais. Ela permite que os servidores restrinjam quais origens de solicitação têm permissão para acessar seus recursos, garantindo que apenas sites confiáveis possam interagir com eles.
</details>

Por essa razão, recomendo o uso do navegador Internet Explorer. <img src="img/image-7.png" alt="Internet Explorer" style="width: 20px; height: 20px;">

Agora, utilize na URL o IP informado na opção do Site Cloner ou digite simplesmente `localhost/` caso o teste seja na própria máquina. 
<details>
<summary>A tela abaixo será exibida:</summary>

![Tela Clonada](/img/image-9.png)

</details>

## Capturando E-mail e Senha 🎣

<details>
<summary>Após inserir o e-mail, senha e clicar em "Entrar", você poderá visualizar no seu console o e-mail e senha capturados:</summary>

![Captura de E-mail e Senha](/img/image-10.png)
</details>

## Observação Importante ⚠️

Este teste de phishing tem fins puramente didáticos e educacionais. O conhecimento adquirido não deve ser usado para obter ganhos ilícitos ou prejudicar terceiros de qualquer forma.

## Contribuições 🤝

Sinta-se à vontade para contribuir com sugestões, correções ou melhorias neste projeto! 🚀
