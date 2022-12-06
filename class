const  todayYear  =  нова  дата ( ) . getFullYear ( ) ;

class  Employee  {
    конструктор ( fullName ,  phoneNum ,  посада ,  освіта ,  yearOfEmployment ,  yearOfDismissal )  {
        це . fullName  =  повне ім'я
        це . phoneNum  =  phoneNum
        це . позиция  =  посада
        це . образование  =  освіта
        це . yearOfEmployment  =  рік роботи
        це . yearOfDismissal  =  рік звільнення
    }

    отримати  позицію ( )  {
        повернути  це . _позиція
    }
    встановити  позицію ( значення )  {
        if  ( [ 'Manager' ,  'JSDeveloper' ,  'SoftTester' ,  'UserExpDesigner' ] . включає ( значення ) )  this . _position  =  значення
        інакше  це . _position  =  false
    }

    get  yearOfEmployment ( )  {
        повернути  це . _yearOfEmployment
    }
    set  yearOfEmployment ( значення )  {
        if  ( value  >  todayYear )  this . _yearOfEmployment  =  false
        інакше  це . _yearOfEmployment  =  значення
    }

    отримати  yearOfDismissal ( )  {
        повернути  це . _yearOfDismissal
    }
    set  yearOfDismissal ( значення )  {
        if  ( value  <  this . _yearOfEmployment )  this . _yearOfDismissal  =  false
        інакше  це . _yearOfDismissal  =  значення
    }
}

const  Employee1  =  новий  співробітник ( 'John Brown' ,  '+001578369320' ,  'SoftTester' ,  'Software engineering' ,  2018 ,  2020 ) ; 
const  Employee2  =  новий  співробітник ( 'Jacob Smith' ,  '+002924590124' ,  'PythonDeveloper' ,  'Software engineering' ,  2027 ,  2025 ) ; 

консоль . журнал ( співробітник1 )
консоль . журнал ( співробітник2 )
