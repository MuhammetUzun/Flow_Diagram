
<h1> Akış Diyagramı ve Algoritma </h1>


<h2>Dizedeki En Küçük Veriyi Bulan Program....</h2>

           int[] array = { 1, 2, -10, 4, 5 };
           
            var minimum = array[0];
            
            for (var i = 0; i <array.Length; i += 1)
            {
                if (array[i]< minimum)
                {
                    minimum = array[i];
                }
            }
            Console.WriteLine(minimum);
            Console.ReadLine();


![image](https://user-images.githubusercontent.com/105195447/205283983-b6b79d40-619d-4c98-9bc2-6f12edae7496.png)
