# Introducao-Ciencia-Computacao-2025
📚 Sobre este Repositório
Este repositório contém materiais e conceitos fundamentais estudados na disciplina de Introdução à Ciência da Computação, abordando desde os fundamentos históricos até ferramentas práticas essenciais para todo desenvolvedor.
🎯 Objetivos

Compreender a evolução histórica da ciência da computação
Dominar conceitos fundamentais da computação
Desenvolver habilidades práticas com terminal e shell
Estabelecer uma base sólida para estudos avançados

📖 Conteúdo Programático
1. História da Ciência da Computação
Marcos Históricos

Pré-História da Computação

Ábaco (3000 a.C.)
Máquina de Antikythera (150-100 a.C.)
Calculadora mecânica de Pascal (1642)


Era dos Pioneiros

Charles Babbage - Máquina Analítica (1837)
Ada Lovelace - Primeiro algoritmo computacional (1843)
Alan Turing - Máquina de Turing e conceitos de computabilidade (1936)


Primeira Geração (1940-1956)

ENIAC (1946)
Válvulas eletrônicas
Programação em linguagem de máquina


Segunda Geração (1956-1963)

Transistores
Linguagens de programação de alto nível
FORTRAN e COBOL


Terceira Geração (1964-1971)

Circuitos integrados
Sistemas operacionais
Multiprogramação


Quarta Geração (1971-presente)

Microprocessadores
Computadores pessoais
Internet e World Wide Web



2. Definições Fundamentais da Computação
O que é Ciência da Computação?
A ciência da computação é o estudo sistemático de algoritmos e estruturas de dados que descrevem e transformam informação, incluindo sua teoria, análise, projeto, eficiência, implementação e aplicação.
Conceitos Essenciais
Algoritmo

Sequência finita de instruções bem definidas
Características: finitude, precisão, entrada, saída, efetividade

Dados vs. Informação

Dados: Fatos brutos sem contexto
Informação: Dados processados com significado

Computação

Processo de utilizar recursos computacionais para resolver problemas
Transformação de entrada em saída através de algoritmos

Sistema Computacional

Hardware + Software + Peopleware
Interação entre componentes físicos e lógicos

Áreas da Ciência da Computação

Algoritmos e Estruturas de Dados
Engenharia de Software
Sistemas Operacionais
Redes de Computadores
Banco de Dados
Inteligência Artificial
Computação Gráfica
Segurança da Informação

3. Terminal e Shell
O que é o Terminal?
O terminal é uma interface de linha de comando que permite interação direta com o sistema operacional através de comandos textuais.
O que é Shell?
Shell é o interpretador de comandos que processa as instruções digitadas no terminal e as executa no sistema operacional.
Tipos de Shell

Bash (Bourne Again Shell) - Padrão no Linux
Zsh (Z Shell) - Popular no macOS
Fish (Friendly Interactive Shell)
PowerShell - Padrão no Windows

Comandos Fundamentais
Navegação
bashpwd          # Mostra diretório atual
ls           # Lista arquivos e diretórios
cd <dir>     # Muda para diretório
cd ..        # Volta um nível
cd ~         # Vai para home
Manipulação de Arquivos
bashtouch <file> # Cria arquivo vazio
mkdir <dir>  # Cria diretório
cp <src> <dest>  # Copia arquivo/diretório
mv <src> <dest>  # Move/renomeia arquivo
rm <file>    # Remove arquivo
rmdir <dir>  # Remove diretório vazio
rm -r <dir>  # Remove diretório recursivamente
Visualização de Conteúdo
bashcat <file>   # Mostra conteúdo do arquivo
less <file>  # Visualiza arquivo paginado
head <file>  # Mostra primeiras linhas
tail <file>  # Mostra últimas linhas
grep <pattern> <file>  # Busca padrão no arquivo
Informações do Sistema
bashwhoami       # Nome do usuário atual
date         # Data e hora atual
uname -a     # Informações do sistema
ps           # Processos em execução
top          # Monitor de processos
df -h        # Espaço em disco
free -h      # Uso de memória
Conceitos Importantes
Path (Caminho)

Absoluto: Caminho completo desde a raiz (/)
Relativo: Caminho em relação ao diretório atual

Wildcards

* - Qualquer sequência de caracteres
? - Qualquer caractere único
[] - Qualquer caractere dentro dos colchetes

Redirecionamento
bashcomando > arquivo    # Redireciona saída para arquivo
comando >> arquivo   # Anexa saída ao arquivo
comando < arquivo    # Usa arquivo como entrada
comando1 | comando2  # Pipe - saída de um vira entrada do outro
Permissões
bashchmod 755 arquivo    # Altera permissões
chown user:group arquivo  # Altera proprietário
🛠️ Ferramentas Recomendadas

Editores de Texto: nano, vim, emacs
Controle de Versão: git
Gerenciadores de Pacotes: apt (Ubuntu), brew (macOS), chocolatey (Windows)
Terminais: Terminal (macOS), WSL (Windows), GNOME Terminal (Linux)
