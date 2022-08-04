//Name: Ayush Verma
//Period: 4B
import java.util.*;

public class ApproximatePI_APP
{
    public static void main(String[] args)
    {
        System.out.println(guessPi(100000000));
    }
    public static double guessPi(int iterations)
    {
        double result = 0.0;
        for (int i = 0; i < iterations; i++)
        {
            if (i % 2 == 0)
            {
                result += 1.0/(2*i+1);
            }
            else
            {
                result -= 1.0/(2*i+1);
            }
        }

        result = 4 * result;

        return result;
    }
}
