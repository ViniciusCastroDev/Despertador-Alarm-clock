
# Despertador / Alarm clock

# [PT-BR]

- O código começa criando uma variável chamada currentTime.
- Esta é a hora do dia para a qual queremos definir nosso alarme.
- O código então cria outra variável chamada content, que conterá o texto em uma tag h1 na página.
- A próxima linha de código cria um seletor para todos os menus de seleção na página e o atribui a uma variável chamada selectMenu.
- O código é usado para definir a hora atual.
- O código define a hora atual usando document.querySelector('h1') e então a define para uma data específica, o que é feito por new Date().
- O código também usa document.querySelector('.content') e document.querySelectorAll('select') para obter o conteúdo da página, para que possa ser atribuído a uma variável chamada content.
- O código começa criando um objeto Audio com o caminho para um arquivo de toque.
- Em seguida, ele cria duas variáveis: alarmTime e isAlarmSet.
- A primeira variável armazena a hora em que o usuário deseja que o alarme dispare em horas, minutos e formato AM/PM.
- A segunda variável armazena se eles já definiram ou não o alarme.
- Em seguida vem uma função chamada setAlarm() que recebe um argumento do tipo boolean (isAlarmSet).
- Esta função retornará true se o usuário já tiver definido seu alarme e false caso contrário.
- Depois, há outra função chamada playRingtone() que reproduz um som de um arquivo mp3 quando chamado.
- Finalmente, há uma propriedade de loop neste objeto de áudio que define sua reprodução para repetir para sempre até que você pare de reproduzi-lo manualmente ou cancele o processo de loop definindo seu valor como false .
- O código será executado quando o alarme for definido.
- O código tocará um toque para notificar o usuário de que seu alarme foi definido.

#[EN]

- The code starts by creating a variable called currentTime.
- This is the time of day for which we want to set our alarm.
- The code then creates another variable called content, which contains the text in an h1 tag on the page.
- The code line creates a selected one for all selection menus and the next one assigns it to a variable called selectMenu
- The code is used to set the current time.
- The code sets a current time using document.querySelector('h1') and then sets it to a specific data, which is done by new Date().
- The code also uses document.querySelector('.content') and document.querySelectorAll('select') to get the page content, so it can be assigned to a variable called content.
- The code starts by creating an Audio object with the path to a ringtone file.
- Then the two variables: alarmTime and isAlarmSet.
- The first variables store the time the user wants the alarm to go off in, minutes and AM/PM format.
- The second variable stored whether or not they already set the alarm.
- Next comes a function called setAlarm() that takes a boolean argument (isAlarmSet).
- This function will return true if the user has already set his alarm and otherwise.
- Then there's another function called playRingtone() that plays a sound from an mp3 file when called.
- Finally, there is a loop property on this audio object that sets its playback to loop forever until you manually stop playing it or cancel the looping process by setting its value to false .
- The code will be executed when the alarm is set.
- The code will play a ringtone to notify the user that their alarm has been set.
