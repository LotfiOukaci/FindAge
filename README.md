
fun main(args: Array<String>) {
    GetAge()
    Getmonth()
    GetDay()
}
fun GetAge(){
    println("please enter the year of your birth")
    var yearBirth= readLine()!!.toInt()
    println("please enter our year (by numbers)")
    var ourYear= readLine()!!.toInt()
    var age=ourYear-yearBirth
    println("your age is:$age")

}
fun Getmonth(){
    println("please enter month of birth")
    var monthBirth= readLine()!!.toInt()
    println("please enter our month (by numbers)")
    var ourMonth=readLine()!!.toInt()
    var monthLeft=monthBirth-ourMonth
    println("it's still:$monthLeft months for your birth day")
}
fun GetDay(){
    println("please enter day of birth")
    var dayBirth= readLine()!!.toInt()
    println("please enter our day (by numbers)")
    var ourDay=readLine()!!.toInt()
    var daysLeft=dayBirth-ourDay
    println("it's still:$dayBirth days for your birth day")
}
