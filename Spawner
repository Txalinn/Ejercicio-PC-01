using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Spawner : MonoBehaviour
{
    public GameObject nuevoCubo;

    public SpawnManagerScriptableObject datosSpawn;

    void Start()
    {
        LlamarCubos();
    }

    void LlamarCubos()
    {
        for (int i = 0; i < datosSpawn.numeroDeCubos; i++)
        {
            Instantiate(nuevoCubo, new Vector3(0, 5, 0), Quaternion.identity);
        }
    }
}
