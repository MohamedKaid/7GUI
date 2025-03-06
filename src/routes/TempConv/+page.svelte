<script>

    class Tempeture{
        #c = $state(0)
        #f = $state(0)


        get c(){
            return this.#c
        }

        set c(temp){

            this.#c=temp
            this.#f=temp*(9/5)+32
        }

        get f(){
            return this.#f
        }

        set f(temp){

            this.#f=temp
            this.#c=(temp-32)*(5/9)
        }
    }

    const tempeture = new Tempeture()
   
</script>


<div>
    <input type="number" bind:value={tempeture.c}/> Celsius = 
    <input type="number" bind:value={tempeture.f}/> Fahrenheit

</div>