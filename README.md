
# Phishing para Captura de Senhas do Facebook (Simulação Educacional)

## Objetivo
Este projeto tem como objetivo educacional demonstrar uma simulação de ataque de phishing para conscientizar sobre os riscos e a importância da segurança cibernética. **Atenção: este conteúdo não deve ser utilizado para fins ilegais.**

## Ferramentas
- Kali Linux
- SEToolkit (Social Engineering Toolkit)

## Passo a Passo

### 1. Configurando o Phishing no Kali Linux

#### Acesso root
Primeiro, obtenha privilégios de superusuário:
```bash
sudo su
```

#### Iniciando o SEToolkit
Execute o comando para iniciar o SEToolkit:
```bash
setoolkit
```

#### Tipo de Ataque
Selecione a opção de ataques de engenharia social:
```
1) Social-Engineering Attacks
```

#### Vetor de Ataque
Escolha a opção para vetores de ataque em sites:
```
2) Web Site Attack Vectors
```

#### Método de Ataque
Escolha o método de captura de credenciais:
```
3) Credential Harvester Attack Method
```

#### Método de Ataque: Site Cloner
Selecione a opção de clonagem de site:
```
2) Site Cloner
```

### 2. Configurando a Rede

#### Obtendo o endereço IP da máquina
Use o comando para identificar o endereço IP local:
```bash
ifconfig
```
Anote o endereço IP, pois será necessário para configurar o phishing.

#### Clonando o site
Insira o URL do site que será clonado:
```
http://www.facebook.com
```
O SEToolkit irá clonar a página de login do Facebook e servir o clone localmente para captura de credenciais.

### 3. Análise dos Resultados
Após a execução do ataque simulado, será possível verificar os dados inseridos na página clonada, permitindo estudar o comportamento do ataque e discutir medidas de defesa.

## Aviso Legal
Este projeto é destinado exclusivamente a **fins educacionais**. A prática de phishing para capturar senhas ou qualquer outra forma de violação de segurança sem o consentimento explícito dos envolvidos é **ilegal e antiética**. Não nos responsabilizamos por qualquer uso inadequado deste conteúdo. Sempre siga as leis locais e as diretrizes éticas da cibersegurança.
