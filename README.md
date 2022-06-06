# Lista de comandos básicos do Git

## 1. Configuração local

### 1.1. Adicionando identificação

```
git config --global user.name
git config --global user.email
```

### 1.2. Configurando o DE/IDE padrão

```
git config --global core.editor code
```

## 2. Fluxo de desenvolvimento local

### 2.1. Inicializar projeto

```
git init
```

### 2.2. Acompanhar estágio atual das alterações

```
git status
```

### 2.3. Separar que deseja registrar no histórico de versionamento

```
git add arquivo.extensão
```

### 2.4. Criar uma descrição para ser adicionado no histórico de versionamento

```
git commit -m "descrição"
```

### 2.5. Listar todo histórico de versionamento do repositório

```
git log
```

## 3. Fluxo de desenvolvimento remoto

### 3.1. Criar uma cópia do repositório localmente

```
git clone
```

### 3.2. Definir qual o endereço do repositório remoto receberá o código-fonte do repositório local

```
git remote add origin https://
```

### 3.3. Enviar o código-fonte do repositório local para o repositório remoto

```
git push
```

### 3.4. Verificar e baixar ajustes no código-fonte do repositório remoto para o repositório local

```
git pull
```
