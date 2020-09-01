# Recursion-methods
Some recursion methods
   
   public int suma(int n) {
        if (n <= 1) {
            return n;
        }
        return n + suma(n - 1);
    }


    public int factorial(int n) {
        if (n <= 1) {
            return n;
        }
        return n * factorial(n - 1);
    }

    public void imprimeHasta(int i, int n) {

        if (i > n) {
            return;
        }
        System.out.println(i);
        imprimeHasta(i + 1, n);

    }

    public int PotenciaDeUnNumero(int base, int expo) {
        if (expo == 0) {
            return 1;
        }

        return base * PotenciaDeUnNumero(base, expo - 1);

    }
