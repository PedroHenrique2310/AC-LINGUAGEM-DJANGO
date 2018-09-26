# AC-LINGUAGEM-DJANGO
ATIVIDADE CONTINUA PARA A DISCIPLINA DE LINGUAGEM DE PROGRAMAÇÃO
-----------------------------------------------------------------------------------------------------------------------------------
Pedro Henrique Souza dos Santos 
Ra 1800402


def save(self):
    if self.email == None or self.email == '':
        self.email == 'email não fornecido'
    print('salvando..')
    super(Professor,self).save()
