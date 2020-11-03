<html>
<head>
<title>Java Visualizer</title>
</head>
<body>
<center><h1>Java Visualizer</h1></center>

<iframe style="width: 100%; height: 480;" src="https://cscircles.cemc.uwaterloo.ca/java_visualize/iframe-embed.html?faking_cpp=false#data=%7B%22user_script%22%3A%22public%20class%20PassByValue%20%7B%5Cn%20%20%20%5Cn%20%20%20static%20void%20reset(int%20x)%20%7B%5Cn%20%20%20%20%20%20x%20%3D%200%3B%5Cn%20%20%20%7D%5Cn%20%20%20%5Cn%20%20%20static%20void%20reset(int%5B%5D%20x)%20%7B%5Cn%20%20%20%20%20%20for%20(int%20i%20%3A%20x)%20%5Cn%20%20%20%20%20%20%20%20%20i%20%3D%200%3B%5Cn%20%20%20%7D%5Cn%20%20%20%5Cn%20%20%20static%20void%20reallyReset(int%5B%5D%20x)%20%7B%5Cn%20%20%20%20%20%20for%20(int%20i%3D0%3B%20i%3Cx.length%3B%20i%2B%2B)%5Cn%20%20%20%20%20%20%20%20%20x%5Bi%5D%20%3D%200%3B%5Cn%20%20%20%7D%5Cn%20%20%20%5Cn%20%20%20public%20static%20void%20main(String%5B%5D%20args)%20%7B%5Cn%20%20%20%20%20%20int%20a%20%3D%203%3B%5Cn%20%20%20%20%20%20int%5B%5D%20arr%20%3D%20%7B5%2C%2010%2C%2015%7D%3B%5Cn%20%20%20%20%20%20reset(a)%3B%20%2F%2F%20this%20won't%20work%5Cn%20%20%20%20%20%20System.out.println(a)%3B%5Cn%20%20%20%20%20%20reset(arr)%3B%20%2F%2F%20this%20won't%20work%5Cn%20%20%20%20%20%20System.out.println(java.util.Arrays.toString(arr))%3B%5Cn%20%20%20%20%20%20reallyReset(arr)%3B%20%2F%2F%20this%20works!%5Cn%20%20%20%20%20%20System.out.println(java.util.Arrays.toString(arr))%3B%5Cn%20%20%20%7D%5Cn%20%20%20%5Cn%7D%22%2C%22options%22%3A%7B%22showStringsAsValues%22%3Atrue%2C%22showAllFields%22%3Afalse%7D%2C%22args%22%3A%5B%5D%2C%22stdin%22%3A%22%22%7D&cumulative=false&heapPrimitives=false&drawParentPointers=false&textReferences=false&showOnlyOutputs=false&py=3&curInstr=0&resizeContainer=true&highlightLines=true&rightStdout=true" frameborder="0" scrolling="no"></iframe>


</body>
</html>
